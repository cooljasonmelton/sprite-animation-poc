# Sprite Animation POC

Small proof-of-concept for animating a sprite sheet with plain HTML and CSS.

5 frames
<https://github.com/user-attachments/assets/01078c8f-70f8-4e4e-ac61-096ab7d44db0>

10 frames
<https://github.com/user-attachments/assets/08cffe54-0a20-4279-a5c6-b3255f37721e>

## What it does

- Loads a sprite sheet image from `assets/`
- Uses CSS `@keyframes` + `steps()` to cycle frames
- Renders a looping animation in the browser

## Project structure

- `index.html`: Demo page and animation styles
- `assets/`: Sprite sheet images used by the demo

## Run locally

1. From this folder, start a static server (example): `python3 -m http.server 8080`
2. Open `http://localhost:8080` in your browser

You can also open `index.html` directly, but a local server is better for consistent asset loading.

## Inspiration

[This blog by Joshua Comeau](https://www.joshwcomeau.com/animation/sprites/)
