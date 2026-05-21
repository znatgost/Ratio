# Ratio — Aspect Ratio Tool

A minimal, beautiful tool for working with aspect ratios and dimensions. Drag to resize, pick a preset, lock the ratio — that's it.

![Ratio Tool](https://img.shields.io/badge/built%20with-vanilla%20JS-d4ff4e?style=flat-square&labelColor=0e0e0e)
![License](https://img.shields.io/badge/license-MIT-d4ff4e?style=flat-square&labelColor=0e0e0e)

## Features

- **Interactive box** — drag any of the 8 handles to resize freely
- **15 built-in presets** — 1:1, 16:9, 4:3, 9:16, 21:9, A4, Cinema Scope and more
- **Lock ratio** — snap the ratio and resize proportionally
- **Live stats** — ratio, decimal value, area, diagonal
- **Manual input** — type exact pixel dimensions up to 10,000 px
- **Preset detection** — automatically highlights when you match a known ratio
- **Mobile ready** — touch support, responsive layout

## Presets

| Name | Ratio | Use case |
|---|---|---|
| Square | 1:1 | Instagram, avatars |
| Classic | 4:3 | Old monitors, photo |
| Photo | 3:2 | DSLR, prints |
| Widescreen | 16:9 | Video, YouTube, TV |
| Ultrawide | 21:9 | Cinema, monitors |
| Portrait | 9:16 | Reels, TikTok, Stories |
| Social | 4:5 | Instagram feed |
| Panorama | 3:1 | Banners, headers |
| Univisium | 2:1 | Film |
| Cinema | 1.85:1 | Hollywood standard |
| Scope | 2.39:1 | Anamorphic / IMAX |
| Monitor | 5:4 | Old LCD screens |
| A4 | 210:297 | Print portrait |
| A4 Landscape | 297:210 | Print landscape |

## Usage

No build step, no dependencies — just open the file.

```bash
git clone https://github.com/znatgost/ratio
cd ratio
open index.html
```

Or drop `index.html` anywhere and open it in a browser.

## Stack

- Vanilla HTML / CSS / JS
- [DM Mono](https://fonts.google.com/specimen/DM+Mono) + [Instrument Serif](https://fonts.google.com/specimen/Instrument+Serif) via Google Fonts
- Zero dependencies, zero build tools

## License

MIT
