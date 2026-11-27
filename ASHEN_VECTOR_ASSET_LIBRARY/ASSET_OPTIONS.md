# Asset Options for ASHEN VECTOR

Choose one coherent visual route before importing. CC0 does not make separately authored packs visually consistent; mixing styles indiscriminately will make the game feel like an asset collage.

## Route A — stylized sci-fi prototype (recommended to get playable quickly)

- **World / modular rooms:** [Quaternius Modular Sci-Fi Megakit](https://quaternius.com/packs/modularscifimegakit.html) — 270+ modular environment items; page lists CC0. A portion is free; full pack and engine-ready editions vary. Page lists FBX, OBJ, and glTF compatibility.
- **Character, enemies, props:** [Quaternius Cyberpunk Game Kit](https://quaternius.com/packs/cyberpunkgamekit.html) — animated character, enemies, platforms, turrets, and other parts; page lists CC0 and FBX, OBJ, glTF, Blend.
- **Weapons:** [Quaternius Sci-Fi Modular Gun Pack](https://quaternius.com/packs/scifimodularguns.html) — modular parts and assembled weapons; page lists CC0 and FBX, OBJ, glTF, Blend.
- **Props / UI / audio / miscellaneous alternatives:** [Kenney 3D assets](https://kenney.nl/assets?type=3d), [Kenney FPS assets](https://kenney.nl/assets?t=fps). Kenney’s pages generally use CC0; check the page for the specific pack you select. The comprehensive all-in-one bundle is optional and paid, not required.

## Route B — build original forms procedurally, then use CC0 surfaces

- Make the player, enemies, guns, pickups, architecture, ammo, and boss from original meshes or blockout geometry. This is the safest way to control silhouettes and create a coherent identity.
- Use [Poly Haven](https://polyhaven.com/) for environment models, HDRIs, and textures. The [license page](https://polyhaven.com/license) states all assets are CC0.
- Use [ambientCG](https://ambientcg.com/) for PBR materials and HDRIs. Its [license page](https://docs.ambientcg.com/license/) states assets are CC0.

## Route C — alternate modular environment / character kits

- [Quaternius asset library](https://quaternius.com/) — browse other themed kits; check the exact page and the included license when downloading.
- [Kenney asset library](https://kenney.nl/assets) — broad 2D, 3D, UI, audio, and texture options. Select only packages whose art style fits your chosen route.
- [Sketchfab downloadable sci-fi models](https://sketchfab.com/search?features=downloadable&type=models&q=sci-fi%20creature) — useful for evaluating options, but each model has its own license. Filter for suitable licenses and verify the individual listing; “downloadable” alone is not permission to ship it.

## Ammo, pickups, and combat readability

These can be simple original low-poly objects and are often better made in-engine than sourced as isolated models. Make health, armor, shells, energy cells, and heavy ammunition distinct by silhouette, icon, and color so the player can identify them during fast combat. Kenney packs can provide placeholders; keep final pickup art within the selected visual route.

## Reference images and visual study

- [Official DOOM Eternal art book](https://gear.bethesda.net/products/the-art-of-doom-eternal-hardcover) — study composition, shape hierarchy, environmental storytelling, and palette. This is a commercial reference source, not a source of game assets.
- [DOOM Eternal rendering presentation](https://advances.realtimerendering.com/s2020/RenderingDoomEternal.pdf) — technical rendering reference.
- [Poly Haven gallery](https://polyhaven.com/) and [ambientCG](https://ambientcg.com/) — browse surface and lighting references with CC0 download options.
- Any image found online should be used as visual reference only unless its license explicitly grants the intended reuse.

## Licensing checklist

1. Open the original asset listing and record the exact pack, author, URL, license, and download date.
2. Preserve the downloaded archive’s included license/readme.
3. Treat packs with unclear terms or a license other than CC0 as “do not ship” until terms are checked.
4. Record selected assets in `ASSET_CREDITS.md`, including modifications and where they appear in the game.
5. Do not use extracted assets from DOOM, DOOM Eternal, or other commercial games.
