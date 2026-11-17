# Paintball Arena 3D

A fast, colorful 3D paintball shooter that runs in the browser — a single `index.html` built with [Three.js](https://threejs.org/).

**Play live:** https://paintball-arena-3d.vercel.app

## Features
- First-person controls with pointer lock, sprint, jump, and crouch
- Paint splats, tracers, muzzle flash, recoil, and elimination particle bursts
- Bots with weaving/dodging movement that shoot you *and each other*
- Player health, hit flash/shake, respawn, 3-minute timed rounds

## Controls
| Action | Key |
| --- | --- |
| Move | W A S D |
| Look | Mouse |
| Jump | Space |
| Sprint | Shift |
| Crouch | C / Ctrl |
| Shoot | Left Click |
| Reload | R |
| Paint color | 1 2 3 4 |

## Run locally
Open `index.html` in a modern desktop browser (needs internet for the Three.js CDN script), or serve it:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.
