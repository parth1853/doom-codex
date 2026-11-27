# ASHEN VECTOR

An original fast, single-player gothic sci-fi arena FPS. Unity is the chosen engine. This repository starts with the concept, asset research, visual direction, and team workflow; the playable Unity implementation is the next milestone.

## Start here

- `GAME_DESIGN.md` — concise vision and first playable scope.
- `CONTRIBUTING.md` — team workflow, branches, reviews, and Unity collaboration notes.
- `Assets/Reference/ASHEN_VECTOR_Art_Direction_Board.png` — original visual direction board.
- `ASHEN_VECTOR_ASSET_LIBRARY/ASSET_OPTIONS.md` — asset routes and license guidance.
- `ASHEN_VECTOR_ASSET_LIBRARY/ANTIGRAVITY_ASSET_BRIEF.md` — prompt for reviewing/importing chosen assets.

## Engine status

Unity is the target engine. The existing root `package.json` is a Vite/Three.js prototype and is not a Unity project. Keep it intact for now; create the Unity project in `UnityProject/` as the next milestone so collaborators can open it without confusing browser prototype files with the game.

## Collaboration

Use feature branches and pull requests. Unity scenes and prefabs are shared as text assets with visible meta files; do not disable Asset Serialization or Version Control Meta Files. Avoid editing the same scene/prefab concurrently. See `CONTRIBUTING.md`.

## License

Project code and original design docs are licensed under MIT (see `LICENSE`). Third-party candidate assets are not bundled except for the original generated concept board and existing workspace reference images. Check each source asset's terms and record selected content in `ASHEN_VECTOR_ASSET_LIBRARY/ASSET_CREDITS.md`.
