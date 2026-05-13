# Contributing

ARC-Room is an early tactical object-intake prototype. Contributions should keep the app lightweight, local-first, and easy to run.

## Good contributions

- Better OBJ/STL parsing reliability.
- GLB/GLTF loader support without bloating the app.
- Accessibility improvements.
- Export schema improvements.
- Command parser improvements.
- Performance improvements for weak hardware.
- Documentation and sample model improvements.

## Design rules

- Keep the base app dependency-free when possible.
- Do not add accounts, cloud services, or required servers.
- Preserve the tactical mesh/HUD visual identity.
- Prefer clear, inspectable code over engine complexity.
- Keep scene export AI-readable.

## Before opening a PR

- Test by opening `index.html` directly.
- Test at least one `.obj` and one `.stl` upload.
- Run the core commands from `docs/COMMANDS.md`.
- Include screenshots if the change affects visuals.
