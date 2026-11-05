![Hand Clap — Frankie Hand Game — current product banner](docs/readme/banner.png)

# Hand Clap — Frankie Hand Game

A browser hand-gesture rhythm game with ink-like visuals, energy management and an on-screen opponent.

## Features

- Follow the three-beat rhythm and choose charging, attack or defense gestures.
- Track player and opponent energy, with multiple attack and defense strengths.
- Adjust the rhythm speed using the interface control.

## Getting started

Serve the directory locally with Python 3:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://localhost:8000. The game loads P5.js, P5.sound and ml5 from external CDNs, and requests camera access for gesture recognition. Actual gameplay needs a working camera permission and model load; opening the source files alone does not verify these.

## Project notes

`index.html` contains the interface and original hand-guide SVG, `style.css` controls presentation, `sketch.js` implements gesture/rhythm/game state, and `sound/` contains audio. No package installation or build step is defined.

## Development

Use the local server to check asset loading, the permission flow, rhythm controls and gameplay. This documentation update did not enable the camera or verify gesture recognition.

Banner sources and update instructions: [README artwork](docs/readme/README.md).
