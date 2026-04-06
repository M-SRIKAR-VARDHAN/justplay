# justplay 🎮

> 7 impossible things running in your browser. No signup. No install. Just play.

---

The web forgot it could be fun. Everything needs an account, a subscription, a cookie banner.

Meanwhile your browser got mass — WebGL, Web Audio, compute shaders and nobody's using it to make things that make you go *"wait, this runs in a BROWSER?"*

**justplay** is a collection of interactive experiments built entirely client-side. No backend. No frameworks. No npm install. Just open a URL and play.

---

## The Experiments

| # | Name | What it is |
|---|------|-----------|
| 1 | **RUBE** | A Rube Goldberg machine where every collision makes music. It always sounds good. |
| 2 | **DRIP** | Paint with physics. Every drip, splash, and accident is beautiful. Tilt your phone. |
| 3 | **GENESIS** | Open the page. Black void. Wait 60 seconds. Life appears. |
| 4 | **WEB** | A harp made of light. Pluck it. Hear music ripple across the screen. |
| 5 | **GHOST LIFE** | Conway's Game of Life, but every generation is a painting. |
| 6 | **SWARM** | Verlet-physics worms that build highway systems from pheromone trails. |
| 7 | **WEATHER** | A planet's entire water cycle — evaporation, clouds, rain — running live in one tab. |

---

## Play Now

🔗 **[justplay →](https://m-srikar-vardhan.github.io/justplay/)**

---

## Tech

- Vanilla JS + Canvas 2D / WebGL
- Web Audio API
- Zero dependencies
- Static site — runs anywhere

---

## Building Blocks

Every experiment is built from a shared library of ~100 reusable building blocks — physics, particles, noise, color, audio, math. They're all in [`blocks/`](./blocks/) and each one has its own mini-demo.

Fork a block. Remix an experiment. Cook your own.

---

## License

MIT — do whatever you want with it.
