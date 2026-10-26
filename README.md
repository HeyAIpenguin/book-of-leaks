# The Book of Leaks

**[Open the book →](https://heyaipenguin.github.io/book-of-leaks/)**

An interactive 3D pop-up book about six real security leaks: Toyota, Uber, SolarWinds, OpenCode, Tailscale and my own Mac. Each spread pops up how the secret got out. Lift the sticky note for what happened next.

[![The Book of Leaks](preview.jpg)](https://heyaipenguin.github.io/book-of-leaks/)

- One HTML file, [Three.js](https://threejs.org) from a CDN, no build step.
- Built with Claude Opus 5.5 in 23 minutes.
- Every number is sourced: see [SOURCES.md](SOURCES.md).

Controls: ← → or the buttons to turn pages, click the sticky notes, drag to look around.

Run it locally: open `index.html` through any static server, e.g. `python3 -m http.server`.

Want to add chapter 7? Fork it: each chapter is one entry in `SPREADS` plus a `build…()` function for its pop-ups.

Check your own machine for leaked keys: [keyaudit](https://github.com/HeyAIpenguin/keyaudit).

By [@HeyAIpenguin](https://x.com/HeyAIpenguin) · MIT License
