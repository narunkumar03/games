# 🎉 Kids Brain Games

A collection of simple, colourful browser games designed to help kids build **memory, focus, pattern recognition, and listening skills** — all in short, playful rounds.

Built as lightweight, self-contained HTML files with no external dependencies, no build tools, and no frameworks. Just open and play. All games are bundled into a single **portal** (`index.html`) with a left navigation sidebar, so kids can jump between games without leaving the page.

---

## 🎮 Games Included

| # | Game | File | Description | Skills Built |
|---|------|------|-------------|---------------|
| 1 | 🎨 **Colour Quest** | `colour-game.html` | Identify the colour shown from four choices. Build a streak for bonus points. | Colour recognition, vocabulary, quick thinking |
| 2 | 🧩 **Shape Sorter** | `shape-sorter.html` | Drag each shape into its matching outline slot. | Pattern recognition, hand-eye coordination |
| 3 | 🧠 **Memory Match** | `memory-match.html` | Flip cards two at a time to find matching pairs. | Short-term memory, concentration, visual recall |
| 4 | 🔍 **Number Riddle** | `number-riddle.html` | Read place-value clues (hundreds/tens/ones) and guess the secret number. | Place value, logical reasoning, number sense |
| 5 | 📝 **Number Names** | `number-names.html` | Type a 3-digit number's name in words, or type the number from its name. | Number names, reading skills, place value |
| 6 | 🔍 **Find the Difference** | `find-difference.html` | Spot and tap the differences between two similar pictures. | Visual attention, focus, detail spotting |
| 7 | 🧩 **Picture Puzzle** | `picture-puzzle.html` | Swap scrambled tiles to rebuild a picture in 45 seconds. | Spatial reasoning, planning, speed under pressure |
| 8 | 👂 **Body Part Sounds** | `body-part-sounds.html` | Listen to a spoken word and tap the matching body part picture. | Listening skills, body awareness, vocabulary |

Every game includes **Easy / Medium / Hard** difficulty levels, a scoring system, and a star rating at the end of each round.

---

## 📁 Project Structure

```
/
├── index.html              # Portal shell — left nav + iframe game viewer
├── colour-game.html         # Colour Quest
├── shape-sorter.html        # Shape Sorter
├── memory-match.html        # Memory Match
├── number-riddle.html       # Number Riddle
├── number-names.html        # Number Names
├── find-difference.html     # Find the Difference
├── picture-puzzle.html      # Picture Puzzle
├── body-part-sounds.html    # Body Part Sounds
└── README.md                 # This file
```

> ⚠️ All files must stay in the **same folder** — the portal loads each game into an iframe using relative paths.

---

## 🖥️ How the Portal Works

- **Left sidebar navigation** lists Home plus all 8 games, each with an icon and short label
- Clicking a game (from the sidebar or the home page cards) loads it **inside an iframe** on the same page — no full page reload
- A **"Back to Home"** button in the game view returns to the landing grid
- On mobile, the sidebar collapses behind a hamburger menu (☰)
- Each game file also works **standalone** if opened directly (e.g. for testing or sharing a single game's link)

---

## ✨ Features

- 📱 **Fully responsive** — works on phones, tablets, and desktops
- 🔌 **Zero dependencies** — no external fonts, libraries, or CDN calls; works fully offline
- 🎚️ **3 difficulty levels** in every game — Easy, Medium, Hard
- ⭐ **Score, streaks, lives, and star ratings** to keep kids motivated
- 🎉 **Confetti animations** on correct answers and game completion
- 🔊 **Built-in text-to-speech** in Body Part Sounds — no audio files needed
- ⏱️ **Countdown timer** in Picture Puzzle for a beat-the-clock challenge
- 🖼️ **Hand-drawn SVG art** throughout — isolated, unambiguous illustrations (no photos or external images)

---

## 🚀 How to Host

### Option 1 — GitHub Pages
1. Push all files to a GitHub repository
2. Go to **Settings → Pages → Source → main branch, / (root)**
3. Your site will be live at:
   ```
   https://YOUR_USERNAME.github.io/YOUR_REPO/
   ```

### Option 2 — Any static web host
Upload all files to any static hosting service (Netlify, Vercel, your own server, etc.) — no server-side setup required.

### Option 3 — Run locally
Just double-click `index.html` to open it in your browser. No local server needed.

---

## 🛠️ Tech Notes

- Pure **HTML, CSS, and vanilla JavaScript** — no React, no build step
- Uses native browser APIs: Canvas (confetti), Pointer Events (drag & drop), CSS 3D transforms (card flips), SpeechSynthesis (spoken words), SVG (all illustrations)
- Games communicate with the portal shell only through the iframe `src` attribute — each game file is fully independent and reusable on its own

---

## 🙌 Credits

Made with ❤️ for curious young minds.
