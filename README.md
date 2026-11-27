# Dirtbox

A tiny pixel-chemistry sandbox. Place materials, watch them fall, flow, drift and react.

## Play

- Choose a material from the left palette.
- Click or drag across the world to paint particles.
- Adjust brush size and density.
- Pause, resume, advance one frame, sample a material or erase.
- Experiment: water meets lava, fire spreads through wood and oil, acid reacts with solids, and steam rises.

## Run locally

This is a dependency-free static app. Open `index.html` in a browser, or run:

```bash
npx serve .
```

## Deploy

Import this repository into Vercel as a static site. No build command or environment variables are required.

## Simulation notes

Dirtbox uses a discrete pixel grid and cellular-automata-style update rules. It is a playful approximation, not a physically exact chemistry or fluid-dynamics solver.
