"# MoonDancer-s-Game" 

# Three.js Artifact Runner
[![Status: WIP](https://img.shields.io/badge/status-WIP-yellow)](https://github.com/your-username/threejs-artifact-runner)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)]

> Browser-based 3D game built with Three.js for the Graphics course. 3 levels, hierarchical models, multiple cameras, lighting & materials.

---

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Project status](#project-status)
- [Quick start](#quick-start)
- [Controls](#controls)
- [Development workflow](#development-workflow)
- [Repository structure](#repository-structure)
- [Design & Technical notes](#design--technical-notes)
- [Assignments / Grading checklist](#assignments--grading-checklist)
- [Contributing](#contributing)
- [License](#license)
- [Credits & Assets](#credits--assets)
- [Contact](#contact)

---

## Demo
*Short GIF / screenshot here (replace with a preview).*  
Live preview (GitHub Pages): `https://your-username.github.io/threejs-artifact-runner/` *(if enabled)*

<img width="1024" height="1536" alt="Pixelated Minecraft Character with Necklace" src="https://github.com/user-attachments/assets/4c3af7f8-2b92-4b5a-92c8-1919f6414ec5" />

---

## Features
- 3 playable levels with increasing difficulty
- Hierarchical models (e.g., turret: base → arm → barrel)
- First-person and third-person cameras with toggle
- Lighting: ambient, directional, and spotlights; shadows enabled
- Collectibles & simple scoring system
- Simple enemy patrol AI (Level 2) and moving platforms (Level 3)
- Minimal HUD (level, score), pause menu, and level transitions

---

## Project status
- Prototype: ✅ basic movement, camera toggle, 3 level groups
- Implemented: Hierarchical turret model, collectibles, basic HUD
- TODO: polish lighting, sound, animations, pathfinding/enemy AI, CI & automated deploy

---

## Quick start

### Requirements
- Modern Chrome (on Ubuntu recommended for grading)
- `git` and optional: `gh` CLI if you use it
- (Optional dev tools) Node.js + npm for build scripts (if the team opts to use them)

### Run locally (no build)
```bash
# clone
git clone https://github.com/your-username/threejs-artifact-runner.git
cd threejs-artifact-runner

# run a simple http server (recommended)
python3 -m http.server 8000
# or: npx http-server . -p 8000

# open in browser
# http://localhost:8000
