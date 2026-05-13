# Release Checklist

## Before release

- [ ] Open `index.html` directly in Chrome/Edge.
- [ ] Open `index.html` directly in Firefox.
- [ ] Upload `sample_models/cube.obj`.
- [ ] Upload `sample_models/pyramid.obj`.
- [ ] Test `/summon cube scale=2 at=0,1,0`.
- [ ] Test `/scale selected 2`.
- [ ] Test `/duplicate selected`.
- [ ] Test `/despawn selected`.
- [ ] Test `/export json`.
- [ ] Test `/save` and `/load`.
- [ ] Confirm README images render on GitHub.
- [ ] Confirm `assets/screenshots/*.webp` files exist.
- [ ] Zip release package without `.DS_Store` or `__MACOSX` files.

## GitHub Pages

Recommended settings:

- Source: Deploy from branch
- Branch: `main`
- Folder: `/root`

The app is static and should run directly from GitHub Pages.
