# shaderdoc

A browser-based shader programming reference and demo collection. Includes an interactive guide covering GLSL fundamentals alongside standalone WebGL demos for advanced effects.

## Contents

### `shader-docs.html` — Shader Programming Guide

An interactive, single-page documentation site covering GPU programming from basics to 3D techniques:

- Animated Gradient Effects
- Procedural Fire Effect
- Wave Animation
- Fractal Brownian Motion (fBm)
- GPU Particle System
- 3D Rotating Cube
- 3D Sphere with Lighting
- 3D Terrain Generation

Each section includes runnable code examples with syntax highlighting (highlight.js, GLSL mode) and a collapsible sidebar for navigation.

### Standalone WebGL Demos

| File | Description |
|------|-------------|
| `liquid-metal.html` | Liquid metal raymarcher |
| `plasma-energy.html` | Plasma energy field effect |
| `sophisticated-raymarcher.html` | Advanced raymarching scene |

## Tech Stack

- **WebGL** — all rendering runs on the GPU in the browser
- **GLSL** — vertex and fragment shaders
- **highlight.js** — syntax highlighting for code examples
- **Vanilla HTML/CSS/JavaScript** — no build step required

## How to Run

Open any `.html` file directly in a WebGL-capable browser:

```bash
open shader-docs.html
# or
open liquid-metal.html
```

## License

Apache License 2.0 — see [LICENSE](LICENSE) for details.
