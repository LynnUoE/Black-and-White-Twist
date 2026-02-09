# Black & White Twist

A dual-perspective puzzle platformer built with Unity. Navigate the same 3D world through two fundamentally different viewpoints — a side-scrolling platformer mode and a top-down strategic mode. The core challenge revolves around timing and spatial reasoning as you coordinate movement with color-phase systems that determine platform accessibility.

## Game Mechanics

### Side View — Platformer Mode
Classic gravity-based movement with jumping. You manually switch your color between black and white to match platforms — only platforms matching your color are solid. Platforms remain static in this mode.

### Top View — Strategic Mode
Grid-based movement with a Phase Dash ability. Platform colors cycle automatically every 3 seconds with a countdown warning. Your color is locked in this mode, so you must time your movement carefully around the shifting platforms.

### Phase Dash
In top view, press Space to dash in your current movement direction. You get one dash per platform, which resets when you land on a new one. Use it to cross gaps and reach distant platforms.

### Color Phase System
Black and white platforms determine where you can stand. You can only interact with platforms that match your current color. In side view, you control the color; in top view, the world shifts around you.

## Controls

| Key | Side View | Top View |
|-----|-----------|----------|
| A / D | Move left / right | — |
| W / A / S / D | — | Move on platform |
| Space | Jump | Phase Dash |
| K | Switch color (black ↔ white) | — |
| Tab | Switch to top view | Switch to side view |

## Tech Stack

- **Engine:** Unity (WebGL Build)
- **Language:** C#
- **Hosting:** GitHub Pages

## Local Development

1. Clone the repository
2. Open the project in Unity
3. File → Build Settings → WebGL → Build
4. Run a local server to test (e.g. `npx serve .`)

## Project Structure

```
├── index.html          # Landing page with embedded game
└── game/               # Unity WebGL build output
    ├── index.html
    ├── Build/
    └── TemplateData/
```
