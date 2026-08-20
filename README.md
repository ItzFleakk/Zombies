# Nightshift // Zombies

A single-file Three.js first-person zombie survival prototype. Open `index.html` through a local web server, then click **Enter the room** to capture the mouse.

## Run

```bash
python3 -m http.server 4173
```

Visit <http://localhost:4173>.

## Controls

- `WASD`: move
- Mouse: aim
- Left click: fire
- `R`: reload

## Remote assets

The game requests optional assets from:

```text
https://raw.githubusercontent.com/ItzFleakk/Zombies/main/assets/
```

Add these files to use custom models:

```text
assets/weapons/pistol.glb
assets/enemies/zombie.glb
```

If either file is unavailable, the game uses a procedural fallback and remains playable. GLTF textures should be stored beside the model or referenced using paths that are valid from its GitHub Raw URL.
