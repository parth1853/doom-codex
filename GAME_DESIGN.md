# ASHEN VECTOR — Game Design

## Vision

Build an original, single-player first-person arena shooter focused on fast, expressive movement, clear enemy roles, meaningful weapon switching, and gothic-industrial science-fiction environments. Take broad genre inspiration from movement-driven arena shooters; do not reuse another franchise's characters, names, story, maps, UI, audio, or signature designs.

## Player fantasy

You are an armored salvage operative sent into a fractured megastructure to destroy rift anchors before an ancient machine intelligence stabilizes a hostile dimension. The player survives by moving decisively, reading attacks, choosing the right weapon, and taking calculated risks for resources.

## Visual identity

- Charcoal stone and oxidized iron; amber furnace light; cyan energy conduits; restrained magenta rift effects.
- Gothic industrial architecture with strong landmarks, layered platforms, and legible routes.
- Distinct silhouettes and non-color cues for enemies, hazards, weak points, and pickups.
- Use `Assets/Reference/ASHEN_VECTOR_Art_Direction_Board.png` as an original mood and composition reference, not a literal asset sheet.

## First playable slice

One 8–12 minute mission: brief onboarding, connected traversal route, two combat arenas, optional reward detour, checkpoint, original multi-phase boss, and completion/replay flow. Prioritize a reliable playable loop over campaign breadth.

### Required pillars

1. Responsive first-person movement: WASD, mouse look, jump, dash, air control, collision, restart.
2. Four distinct weapons: close burst, precision, rapid energy, and heavy explosive/charged.
3. Four enemy roles: fragile ranged skirmisher, melee hunter, zoning artillery, durable elite.
4. Combat readability: clear attack tells, vulnerability windows, distinct projectiles, hit feedback.
5. Progression: health/armor/ammo pickups, one optional gameplay upgrade, checkpoint, mission reward.
6. Menus and HUD: title, pause, settings, health, armor, weapon/ammo, reticle, dash state, boss health, death and completion.

## Technical target

- Engine: Unity, targeting a current supported LTS release selected when the Unity project is created.
- Prefer the Unity Input System and URP unless the team documents a reason otherwise.
- Build modular systems for player, weapons, enemies, encounters, pickups, UI, and mission flow.
- Keep tuning data centralized; avoid giant monolithic scripts.
- No online services, accounts, API keys, telemetry, or paid dependencies.

## Definition of a successful first milestone

Unity project opens cleanly; one greybox arena is playable; movement, mouse look, jump, dash, collision, and restart work; one weapon can damage a target; HUD communicates state; README setup steps are accurate; a teammate can clone and open the project.
