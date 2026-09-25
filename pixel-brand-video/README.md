# Arzbar Pixel Brand Video

HyperFrames source for a 30-second, 16:9 Traditional Chinese brand promo based on the warm ArzbarPage branch. See `BRIEF.md`, `DESIGN.md`, and `STORYBOARD.md` for the content and visual decisions.

## Local preview / render

Requires Node.js, pnpm, Python 3, and FFmpeg. Mixkit audio is intentionally excluded from Git. Read `LICENSES.md`, then from this directory run:

```powershell
python scripts/fetch_mixkit.py get-music 175
python scripts/fetch_mixkit.py get-sfx 1490 2350 2568 2631 2634 3124
npx hyperframes@0.8.77 check --snapshots
npx hyperframes@0.8.77 preview
```

The audio files are written under `audio/` and are ignored by Git. For an approved final export, render from HyperFrames and verify the resulting MP4 with `ffprobe`.

This composition is authored for local preview; the site font stack falls back to fonts available on the render machine.
