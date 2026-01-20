# Vector Shooter

[![Play Vector Shooter](https://img.shields.io/badge/▶%20Play-Vector%20Shooter-brightgreen?style=for-the-badge)](https://jayjonesvip.github.io/vector-shooter/)

![Game Status](https://img.shields.io/website?url=https://jayjonesvip.github.io/vector-shooter/&label=Game%20Status)
![Last Commit](https://img.shields.io/github/last-commit/jayjonesvip/vector-shooter)


A lightweight HTML5 canvas arcade shooter with clean vector visuals, simple controls, increasing difficulty, and sound effects.

## ▶ Play the Game
**Live demo:**  
https://jayjonesvip.github.io/vector-shooter/

Runs directly in the browser — no build step required.

## Controls
- **W / S** or **↑ / ↓**: Move
- **Space**: Shoot
- **P**: Pause
- **Enter**: New Game (when Game Over)

## Gameplay
- You pilot a small vector ship and survive incoming hazards.
- Shoot enemies to score points.
- Difficulty ramps up over time (spawn rate increases, speed rises).
- You have **3 HP**.
- If you get hit:
  - You respawn after a short countdown (if you still have HP).
  - If HP hits 0, it’s **Game Over** and your score is shown.

## Features
- Single-file game (`index.html`)
- Responsive canvas sizing (fits most screens)
- Vector-style art (grid, outlined shapes, minimal neon palette)
- Particles/explosions on hits
- SFX support:
  - `shoot.mp3`
  - `hit.mp3`
  - `death.mp3`
- Overlay UI for **death countdown** and **game over**

## Run Locally
Just open `index.html` in your browser.

## License
MIT (or choose your preferred license)
