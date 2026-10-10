# Klayworld — first-person environment prototype

A small browser-based 3D walking prototype inspired by the handmade clay environments of classic clay-animation adventure games.

## Run
1. Open `index.html` in a current desktop browser.
2. If your browser blocks ES-module imports from local files, run a local static server in this folder:
   - Python: `python -m http.server 8000`
   - Then open `http://localhost:8000`
3. Click **ENTER THE WORLD**.

An internet connection is needed to load Three.js from jsDelivr.

## Controls
- W / A / S / D: move
- Mouse: look around (pointer lock)
- Space: hop
- Shift: move faster
- Esc: release the mouse

## What's included
- Procedural clay-like island terrain and irregular forms
- Round house, monumental hall, arches, pipework, mushroom-like trees, pond, bridge and distant floating landforms
- Basic first-person camera controller and shadows/fog
- No original game files or extracted assets

## Prototype limitations
This is a procedural proof of concept, not a faithful reconstruction of every original room or a production-ready game engine. It uses simple geometry rather than scanned clay meshes or physically based clay scans. The next development phase would be reference-led blockouts of specific locations, collision meshes, interactive objects, a saveable world/scene format, and higher-detail sculpted assets.
