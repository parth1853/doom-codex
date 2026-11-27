# Contributing to ASHEN VECTOR

Thanks for helping build the game. The project is at the design/bootstrap stage; coordinate before building systems so we agree on Unity version, render pipeline, input system, and folder conventions.

## Workflow

1. Create a feature branch from `main`: `feature/<short-description>` or `fix/<short-description>`.
2. Keep each pull request focused and describe how the change was checked in Unity.
3. Request at least one teammate review before merging.
4. Do not commit generated build output, `Library/`, `Temp/`, `Obj/`, `Logs/`, or local IDE state.
5. Keep Unity `.meta` files. Use text serialization and visible meta files.
6. Avoid simultaneous edits to the same scene or prefab. Coordinate ownership or split work into separate scenes/prefabs.
7. Never commit credentials, private keys, paid asset packs, or assets without documented reuse terms.

## Unity collaboration rules

- Unity project will live in `UnityProject/`.
- Pin the Unity editor version in `UnityProject/ProjectSettings/ProjectVersion.txt` once the project is created.
- Use Unity YAML/text serialization and `Visible Meta Files`.
- Use Git LFS for large binary files only when the team agrees on quotas and file patterns. Prefer source assets that are appropriately optimized for the target build.
- Put external assets in clearly named folders and preserve license/readme files. Update `ASHEN_VECTOR_ASSET_LIBRARY/ASSET_CREDITS.md`.
- Do not import every candidate asset. Choose one coherent art route and keep unselected options outside the Unity project.

## Pull request checklist

- [ ] Change has a clear purpose and does not include unrelated generated files.
- [ ] Project opens and relevant scene/prefab works in the pinned Unity version.
- [ ] New assets have source and license recorded.
- [ ] Controls/UI remain readable and accessible.
- [ ] Known limitations are stated in the pull request.
