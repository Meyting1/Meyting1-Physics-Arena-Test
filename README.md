# NEON PITCH — Physics Lab

A mobile-friendly, browser-playable prototype for the NEON PITCH project.

## Run it
Open `index.html` in a modern browser, or enable GitHub Pages for this repository and publish from the `main` branch / root folder.

## Current prototype
- Top-down neon arena with touch and mouse controls.
- Drag back from the cyan striker and release to shoot.
- Sub-stepped circle collision solver with overlap correction, restitution and tangential friction.
- Rolling drag, wall rebounds, impact particles, trails and optional synthesized sound.
- Basic local AI opponent and score/reset loop.

## Important
This is an early single-device physics prototype. It does **not** yet include online matchmaking, rooms, accounts, persistent balances, ads, or TON payments. Those systems should be added only after the core movement and collision feel has been tested and tuned.

## Next physics milestones
1. Tune restitution, friction and mass ratios against repeatable test shots.
2. Add deterministic replay/debug overlays for collision vectors and velocity.
3. Test on low-end Android hardware and tune frame pacing.
4. Add robust goal-mouth collision rules and richer impact feedback.
