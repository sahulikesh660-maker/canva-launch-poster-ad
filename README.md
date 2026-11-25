# Canva — Launch Poster (90 s, 9:16)

A HyperFrames promotional ad. Picked storyline: **Launch Poster** (see `STORYLINES.md`);
the director's brief with every number is `SPEC.md`.

## Files

- `index.html` — root composition: 9 scene hosts, music and SFX.
- `compositions/` — one pauseable timeline per scene.
- `assets/brand/` — Canva's own favicon mark and wordmark (fetched from canva.com / Wikimedia Commons).
- `assets/ui/` — real Canva page plates captured by `.github/workflows/capture.yml`.
- `assets/audio/` — music bed and bundled/Openverse SFX.
- `.github/workflows/render.yml` — renders the film and uploads the MP4 as an artifact.

## Render on GitHub

Push a commit, then:

```
gh workflow run render.yml
gh run list --workflow=render.yml
```

The workflow downloads the `canva-ui` artifact when one exists, installs the pinned
HyperFrames CLI, runs `check`, renders `canva-launch-poster.mp4` at 1080×1920 / 30 fps,
verifies it with `ffprobe`, and uploads the MP4 plus decoded QA frames as artifacts.

## Credits

- Canva mark and wordmark: Canva's own brand files.
- Real page plates: captured from public Canva pages.
- Music: SoundHelix Song 1 (free example track, https://www.soundhelix.com/) — trimmed to 90 s,
  faded and loudness-matched. Swap for a licensed track for commercial use.
- SFX: HyperFrames bundled library / Openverse, CC BY; see `.media/audio/sfx/CREDITS.md`.
