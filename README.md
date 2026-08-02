# 🎉 Kids Brain Games

A collection of simple, colourful browser games designed to help kids build **memory, focus, and pattern recognition** — all in short, playful rounds.

Built as lightweight, self-contained HTML files with no external dependencies, no build tools, and no frameworks. Just open and play.

---

## 🎮 Games Included

| Game | File | Description | Skills Built |
|------|------|-------------|---------------|
| 🎨 **Colour Quest** | `colour-game.html` | Identify the colour shown from four choices. Build a streak for bonus points. | Colour recognition, vocabulary, quick thinking |
| 🧩 **Shape Sorter** | `shape-sorter.html` | Drag each shape into its matching outline slot. | Pattern recognition, hand-eye coordination |
| 🧠 **Memory Match** | `memory-match.html` | Flip cards two at a time to find matching pairs. | Short-term memory, concentration, visual recall |
| 🏠 **Home / Landing Page** | `index.html` | Navigation hub linking to all three games with info about each. | — |

---

## 📁 Project Structure

```
/
├── index.html          # Landing page — links to all games
├── colour-game.html     # Colour Quest game
├── shape-sorter.html    # Shape Sorter game
├── memory-match.html    # Memory Match game
└── README.md            # This file
```

> ⚠️ All four files must stay in the **same folder** — the landing page links to the games using relative paths.

---

## ✨ Features

- 📱 **Fully responsive** — works on phones, tablets, and desktops
- 🔌 **Zero dependencies** — no external fonts, libraries, or CDN calls; works fully offline
- 🎚️ **3 difficulty levels** in every game — Easy, Medium, Hard
- ⭐ **Score, streaks, and star ratings** to keep kids motivated
- 🎉 **Confetti animations** on correct answers and game completion
- ❤️ **Lives system** in Colour Quest and Shape Sorter for a light challenge

---

## 🚀 How to Host

### Option 1 — GitHub Pages
1. Push all files to a GitHub repository
2. Go to **Settings → Pages → Source → main branch**
3. Your site will be live at:
   ```
   https://YOUR_USERNAME.github.io/YOUR_REPO/
   ```

### Option 2 — Any static web host
Upload all four files to any static hosting service (Netlify, Vercel, your own server, etc.) — no server-side setup required.

### Option 3 — Run locally
Just double-click `index.html` to open it in your browser. No local server needed.

---

## 🛠️ Tech Notes

- Pure **HTML, CSS, and vanilla JavaScript** — no React, no build step
- Uses native browser APIs: Canvas (confetti), Pointer Events (drag & drop), CSS 3D transforms (card flips)
- Emoji used instead of image assets to keep file size small and avoid broken links

---

## 🙌 Credits

Made with ❤️ for curious young minds.
