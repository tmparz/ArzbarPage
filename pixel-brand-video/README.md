# Arzbar Pixel Stage Brand Video

A 30-second, 16:9 HyperFrames composition aligned to the pixel-game interface on ArzbarPage's pixel-stage-theme branch.

## Project
- index.html: four 7.5-second scenes, music, short cues, and orange pixel-grid wipes.
- compositions/frame-*.html: Stage 01 diagnosis, Stage 02 connected platform, Stage 03 Solve Mode, final CTA.
- assets/arz-pixel-mascot.svg: pixel character from the site's inline SVG.
- assets/fonts: bundled Press Start 2P font and SIL Open Font License.
- frame.md, BRIEF.md, DESIGN.md, STORYBOARD.md: creative direction and production specs.

## Build
Pinned to HyperFrames 0.8.77. Run pnpm dlx hyperframes@0.8.77 check --snapshots, then render with delivery quality. Audio MP3s remain local and ignored by Git; reacquire them with scripts/fetch_mixkit.py. Audio license records are in LICENSES.md and THIRD_PARTY_LICENSES.md.
