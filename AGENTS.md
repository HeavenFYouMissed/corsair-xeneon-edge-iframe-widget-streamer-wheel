# AGENTS.md

## Cursor Cloud specific instructions

This repo is a set of self-contained, static HTML/CSS/JS stream widgets for the Corsair Xeneon Edge monitor. There is no backend, no build step, no package manager, no tests, and no dependencies. See `README.md` for the widget descriptions and end-user (copy/paste into the monitor) workflow.

### Widgets
- `wheel-neon.html`, `wheel-glass.html`, `wheel-pastel.html` — drag-to-spin giveaway wheels. Segment count is set via URL hash, e.g. `wheel-neon.html#50` (default 100).
- `slot-machine.html` — 5-reel 3D slot machine; starts with 1000 credits, pull the lever to spin.

### Running locally
- Serve the files over HTTP from the repo root and open them in a browser, e.g. `python3 -m http.server 8080` then visit `http://localhost:8080/slot-machine.html`. Node's `npx serve` works too. A real HTTP server is preferable to `file://` so behavior matches the iframe widget environment.

### Lint / test / build
- None exist. There is no linter, test suite, or build command in this repo — validate changes by opening the widgets in a browser and interacting with them (spin a wheel, pull the slot lever).
