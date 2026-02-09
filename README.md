# Black & White Twist

A 3D-puzzle-platformer where changing perspectives reveals hidden truths. Use side-view jumping and color switching. Then dash in top-down planning mode through changing platform colors to uncover safe paths, where only timing and viewpoint grant passage.

## Developers

- Aryan Sindhu [@aryansindhu8](https://github.com/aryansindhu8)
- Linxuan Chen [@lynnuoe](https://github.com/lynnuoe)

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
