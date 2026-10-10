# Chord Piano 🎹

A tiny interactive piano for learning chords by **semitone distance**.

<!-- derpcat-support -->
<p align="center">
  <a href="https://www.patreon.com/derpcatmusic">
    <img src=".github/support-derpcat.svg" alt="Donate to Derpcat on Patreon — support my open-source work and help me keep building and maintaining free tools." width="800">
  </a>
  <br>
  <a href="https://www.patreon.com/derpcatmusic"><strong>❤️ Support me on Patreon</strong></a>
</p>
<!-- /derpcat-support -->

Examples:

- Major = `4 + 3`
- Minor = `3 + 4`
- Diminished = `3 + 3`
- Augmented = `4 + 4`
- Major 7 = `4 + 3 + 4`
- Dominant 7 = `4 + 3 + 3`
- Minor 7 = `3 + 4 + 3`

## Features

- Click piano keys to build a chord
- Detects common triads and seventh chords
- Shows semitone jumps between chord tones
- Shows root-relative intervals
- Root selector + chord presets
- Inversions
- In-browser audio with Web Audio
- Works as one static HTML file
- No framework, dependencies, analytics, or build step

## Run locally

Open `index.html` directly, or run:

```bash
python -m http.server 8000
```

## GitHub Pages

In the repository, go to **Settings → Pages**, choose **Deploy from a branch**, then select `main` and `/ (root)`.

The site will be available at:

`https://derpcatmusic.github.io/chord-piano/`

## License

MIT
