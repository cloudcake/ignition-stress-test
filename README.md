# Ember Stress Test Pack

Real scanned models and 2K PBR textures used by the Ember editor's Stress Test template, so its
performance readings reflect real-world content instead of low-poly stand-ins.

- Everything here is CC0 (public domain) from Poly Haven; see `LICENSE.txt` for each source.
- The editor downloads the release zip (`ember-stress-test-pack-v<N>.zip`) on first use into a
  per-user cache, checks its SHA-256 and `manifest.json`, then copies it into the project's
  `Stress Test Pack` folder. Nothing here ships inside the editor.
- A new version gets a new release tag (`v2`, ...) and a new hash in the editor.

| Folder | Contents |
|---|---|
| `Models/` | Geometry-only `.glb` files, one mesh each, scaled to the template's sizes |
| `Textures/` | 2K JPEG albedo, OpenGL normal and ARM (occlusion, roughness, metallic) maps |
| `Materials/` | Ember `.mat` files that point at the textures |
| `manifest.json` | Size and SHA-256 of every file |
