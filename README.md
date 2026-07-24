# 🚀 Space Game

A fast-paced, canvas-based space shooter built with vanilla HTML5, CSS, and JavaScript. Featuring a live HUD, customizable settings, and a leaderboard — all playable directly in the browser.

**[▶ Play it live](https://spacegame-6swo.onrender.com)**

## Features

- **Canvas rendering** — smooth, real-time gameplay powered by the HTML5 `<canvas>` element
- **Live HUD** — tracks Score, Level, Lives, Shield %, FPS, and elapsed Time
- **Pause / Resume / Restart** — full game state control mid-session
- **Settings panel**
  - Difficulty: Easy, Normal, Hard, Insane
  - Graphics quality: Low, Medium, High, Ultra
  - Music & SFX volume controls
  - Control scheme: WASD + Space, Arrows + Space, or Custom
- **Leaderboard** — track top scores
- **Fullscreen & mute toggles**
- **Accessible controls** with keyboard support throughout

## Controls

| Action | Key |
|---|---|
| Move | Arrow keys or `WASD` |
| Fire | `Space` |
| Special | `Shift` |
| Pause | `P` |
| Toggle Fullscreen | `F` |

## Getting Started

### Play online
Just visit the [hosted version](https://spacegame-6swo.onrender.com) — no install required.

### Run locally
```bash
git clone https://github.com/your-username/spacegame.git
cd spacegame
```

Then simply open `index.html` in your browser, or serve it locally:

```bash
npx serve .
```

## Project Structure

```
spacegame/
├── index.html      # Main game markup & UI (HUD, settings, dialogs)
├── app.js          # Game logic — canvas rendering, input handling, audio
├── styles.css       # Styling and layout
└── README.md
```

## Tech Stack

- HTML5 Canvas
- Vanilla JavaScript
- CSS3

## Deployment

This project is deployed on [Render](https://render.com).
