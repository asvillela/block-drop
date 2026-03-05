# 🎮 Block Drop

A fully-featured, single-file block puzzle game built with HTML, CSS, and vanilla JavaScript. Inspired by classic falling-block games. Playable in any browser — no installs, no dependencies.

🕹️ **[Play it live →](https://YOUR-USERNAME.github.io/block-drop/blockdrop.html)**

---

## Features

- **SRS Rotation System** — Standard wall kicks for accurate piece rotation
- **Ghost Piece** — Shows where your piece will land
- **Hold Piece** — Swap and save a piece for later
- **7-Bag Randomizer** — Fair piece distribution
- **Increasing Difficulty** — Speed ramps up every 10 lines
- **Score System** — Points for singles, doubles, triples, and quad clears
- **Best Score** — Saved locally in your browser
- **🌋 Earthquake Mode** — Special button that scrambles all placed blocks
- **Keyboard + Touch Controls** — Works on desktop and mobile
- **Retro CRT Aesthetic** — Scanlines, glow effects, and neon colors

---

## Controls

### Keyboard

| Key | Action |
|-----|--------|
| `←` `→` | Move left / right |
| `↓` | Soft drop |
| `↑` or `Z` | Rotate |
| `Space` | Hard drop |
| `C` | Hold piece |
| `P` / `Esc` | Pause / Resume |

### On-Screen Buttons

All controls are available as touch-friendly buttons below the game board — works great on mobile.

---

## Scoring

| Action | Points |
|--------|--------|
| Single | 100 × level |
| Double | 300 × level |
| Triple | 500 × level |
| Quad clear | 800 × level |
| Soft drop | 1 per row |
| Hard drop | 2 per row |

---

## How to Run Locally

No build steps needed. Just open the file:

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/block-drop.git

# Open in your browser
open blockdrop.html
```

Or drag `blockdrop.html` directly into any browser window.

---

## Tech Stack

- **HTML5 Canvas** — Game rendering
- **Vanilla JavaScript** — All game logic
- **CSS Animations** — UI effects and screen shake
- [Orbitron](https://fonts.google.com/specimen/Orbitron) + [Share Tech Mono](https://fonts.google.com/specimen/Share+Tech+Mono) — Google Fonts

---

## Built With

This game was built with the help of [Claude](https://claude.ai) by Anthropic — used for writing and iterating on the code, documentation, and project setup.

---

## License

MIT — free to use, remix, and share. See [LICENSE](LICENSE).
