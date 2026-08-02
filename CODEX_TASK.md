# Codex task — 512 Voxel Holographic TV

Work in the repository `teslaeco/512-Voxel-Holographic-TV`.

## Goal

Develop this repository into a professional public presentation and future prototype workspace for a volumetric television concept built from 512 independently controlled spatial cells arranged as an 8 × 8 × 8 cube.

## Requirements

1. Preserve the project origin in Cube Chess 512 and clearly explain that 8 × 8 × 8 equals 512 spatial positions.
2. Keep the concept film at `media/512-voxel-holographic-tv-concept.mp4`.
3. Keep and display both visualizations:
   - `assets/512-voxel-holographic-tv-clean-concept.jpg`
   - `assets/512-voxel-holographic-tv-grid-concept.jpg`
4. Keep a prominent PLAY button near the top of `README.md` linking directly to the MP4 film.
5. Do not claim that a physical prototype already exists. Clearly label the project as an early concept and visual research project.
6. Explain possible technical approaches without presenting any unverified method as solved:
   - stacked transparent display layers,
   - independently controlled voxel modules,
   - volumetric projection media,
   - light-field display techniques,
   - hybrid projection and viewer-tracking systems.
7. Explain the major challenges: transparency, brightness, optical cross-talk, wiring, synchronization, heat, viewing angle and scaling to higher resolution.
8. Preserve the authorship notice for Sebastian Laskowski / TeslaEco and the current all-rights-reserved position unless the repository owner explicitly changes the licence.
9. Use clean Markdown, accessible alt text and relative repository links.
10. Before committing, verify that every image and film link in the README resolves to an existing file with the exact same capitalization.

## Suggested next implementation

Create a browser-based 8 × 8 × 8 voxel simulator using Three.js or another lightweight WebGL library. It should:

- render 512 selectable voxels,
- allow orbit, zoom and layer filtering,
- animate colour and opacity per voxel,
- load a simple sequence from JSON,
- include a Cube Chess demo mode,
- work on desktop and mobile,
- avoid replacing the existing README or media assets.

Use a separate feature branch and open a pull request. Include screenshots and testing instructions in the PR description.
