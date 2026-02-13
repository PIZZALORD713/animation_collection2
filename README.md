# animation_collection2

Animation source pack for `frienemies.xyz`.

## Add a new animation
1. Upload your `.glb` file(s) to this repo root (or keep in a subfolder and use full path in URL).
2. Add an entry in `animations.json` with display name + CDN URL.
3. Commit + push.
4. Viewer will load from jsDelivr manifest URL:
   `https://cdn.jsdelivr.net/gh/PIZZALORD713/animation_collection2@main/animations.json`

## Manifest format

```json
[
  {
    "name": "Idle2",
    "url": "https://cdn.jsdelivr.net/gh/PIZZALORD713/animation_collection2@main/Idle2.glb"
  },
  {
    "name": "Dance1",
    "url": "https://cdn.jsdelivr.net/gh/PIZZALORD713/animation_collection2@main/Dance1.glb"
  }
]
```

Array-pair format also works:

```json
[
  ["Idle2", "https://cdn.jsdelivr.net/gh/PIZZALORD713/animation_collection2@main/Idle2.glb"]
]
```
