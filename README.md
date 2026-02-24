# Sprite Animation POC

Small proof-of-concept for animating a sprite sheet with plain HTML and CSS.

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
