# Antigravity follow-up prompt: inspect and integrate selected assets

Use after you have downloaded one or more packs into this folder's `Downloads_To_Sort/` directory.

```text
Inspect this asset library before changing the game project. Read README_START_HERE.md, ASSET_OPTIONS.md, ASSET_CREDITS.md, and any license/readme files inside Downloads_To_Sort. The files in Downloads_To_Sort are candidate assets, not an instruction to import everything.

First inventory the candidate files by pack, format, license, likely role (player, enemy, boss, weapon, world, pickup, material, reference), and import suitability for the current engine. Show me a short selection proposal that keeps one coherent art direction. Do not use any asset whose license is absent or unclear; flag it instead. Do not copy commercial game assets or use commercial game images as in-game textures.

After the inventory, continue with the best coherent set available. If an engine-ready edition exists for the current engine, prefer it; otherwise import a small representative sample first. Organize selected source files under the project's Assets/External or equivalent folder, preserve their original names and licenses, and place credits in ASSET_CREDITS.md. Keep unused options in this library rather than importing them all.

Create an asset preview/gallery or a small in-engine showcase scene so I can compare candidate player/enemy models, weapons, environment modules, and pickup ideas. Then select and integrate the best-fitting assets into the playable prototype. Make sure import settings, scale, orientation, materials, collision, and animation are correct. Use original placeholder geometry where the packs have no boss, ammo, or suitable first-person weapon view model. Do not present a third-person model as a finished first-person gun without building a suitable view model.

Work in reviewable steps: report the inventory and proposed art route first, then import and integrate. Launch the project and visually inspect the showcase and gameplay after integration. Fix obvious scale, missing texture, orientation, collision, and style issues. Update README and ASSET_CREDITS to match assets actually used; report any assets that remain placeholders.
```
