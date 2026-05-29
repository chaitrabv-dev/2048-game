# 🎮 2048 — Epic Edition

> A stunningly visual, audio-enhanced 2048 game with Brain Rating, Combo Streaks & full Stats Card — playable right in your browser. No installs. No backend. Just pure fun.

🔗 **[Play Now → chaitrabv-dev.github.io/2048-game](https://chaitrabv-dev.github.io/2048-game)**

---

## ✨ Features

### 🎨 Visual Design
- Cosmic animated background with 120 twinkling stars
- Neon gradient tiles — every number has its own unique glow
- Glassmorphism board with depth and blur effects
- Particle explosions on every merge
- Floating +score popups on tile combinations
- Fully responsive — works on desktop, tablet & mobile

### 🔊 Sound Effects *(Web Audio API — no files needed)*
| Action | Sound |
|---|---|
| Tile slide | Soft low whoosh |
| Tile merge | Musical chime scaled to tile value |
| Combo streak | Rising arpeggio sparkle |
| New tile spawn | Tiny soft pop |
| Game Over | 3 descending sad tones |
| You Win! | Triumphant ascending fanfare |
| New Game | Upward sweep |

Toggle sound on/off with the 🔊 button anytime.

### 🧠 Brain Rating System
Your efficiency (score ÷ moves) earns you a brain tier:

| Rating | Efficiency | Top % |
|---|---|---|
| 🧠 Galaxy Brain | 55+ pts/move | Top 5% |
| ⚡ Sharp Mind | 38+ pts/move | Top 22% |
| 😎 Street Smart | 22+ pts/move | Top 43% |
| 🎯 Calculated | 12+ pts/move | Top 64% |
| 🐒 Monkey Mode | Below 12 pts/move | — |

### 🔥 Live Combo Streak
Merge tiles consecutively to build your streak:
- `🔥 Warming Up` — 2–3 in a row
- `🔥🔥 On Fire!` — 4–5 in a row
- `💥 BLAZING!` — 6–8 in a row
- `⚡ UNSTOPPABLE!` — 9+ in a row *(pulsing glow)*

### 📊 End Game Stats Card
When the game ends you get a full report:
- 🏆 Final Score
- 🎯 Total Moves
- ⭐ Highest Tile Reached
- ⚡ Points Per Move (Efficiency)
- 🔥 Best Combo Streak
- ⏱️ Time Played
- 🧠 Brain Rating with percentile bar

---

## 🕹️ How to Play

| Control | Action |
|---|---|
| ← → ↑ ↓ Arrow Keys | Move tiles (desktop) |
| Swipe | Move tiles (mobile/touch) |
| On-screen buttons | Move tiles (small screens) |
| 🔊 Button | Toggle sound |
| ✨ New | Start a new game |

Tiles with the same number **merge** when they collide. Keep merging until you reach **2048** — or go beyond!

---

## 🚀 Tech Stack

- **Pure HTML5 + CSS3 + Vanilla JavaScript**
- **Web Audio API** — all sounds generated procedurally, zero audio files
- **CSS animations** — tile pop, merge, star twinkle, streak pulse
- **Canvas API** — particle explosion system
- **localStorage** — best score persisted across sessions
- Zero dependencies · Zero frameworks · Single file

---

## 📁 Project Structure

```
2048-game/
└── index.html    ← The entire game (HTML + CSS + JS in one file)
└── README.md     ← You are here
```

---

## 🛠️ Run Locally

No setup needed:

```bash
git clone https://github.com/chaitrabv-dev/2048-game.git
cd 2048-game
# Just open index.html in any browser!
open index.html
```

---

## 🌐 Deploy Your Own

This game is a single HTML file — host it anywhere:

| Platform | How |
|---|---|
| **GitHub Pages** | Push to repo → Settings → Pages → main branch |
| **Netlify** | Drag & drop the folder at netlify.com |
| **Vercel** | `vercel` CLI or import from GitHub |
| **Any web host** | Upload `index.html` via FTP |

---

## 🙌 Credits

Built with ❤️ by [Chaitra BV](https://chaitrabv-dev.github.io) · Inspired by the original [2048](https://gabrielecirulli.github.io/2048/) by Gabriele Cirulli.

---

## 📄 License

MIT License — free to use, share, and remix.
