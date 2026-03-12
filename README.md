<div align="center">

# 🎲 Ludo Game

**A classic 4-player Ludo board game built with pure HTML, CSS & JavaScript**

<img width="1791" height="887" alt="image" src="https://github.com/user-attachments/assets/6617ef25-fe86-407b-a9bd-6ffc7e1a0b41" />


*Vibe coded with ❤️ — no frameworks, no build tools, just vibes*

</div>

---

## 📸 Screenshots

<div align="center">

| Game Board | Winning Screen |
|:---:|:---:|
| ![Game Board](screenshots/board.png) | ![Win Screen](screenshots/win.png) |

| Player Turn | Token Selection |
|:---:|:---:|
| ![Player Turn](screenshots/turn.png) | ![Token Select](screenshots/select.png) |

</div>

> 📌 **To add screenshots:** Create a `screenshots/` folder in the repo root and add your images as `board.png`, `win.png`, `turn.png`, `select.png`

---

## 🎮 How to Play

1. Open `index.html` in any browser — no installation needed
2. Each player takes turns rolling the dice
3. Roll a **6** to bring a token out of home base
4. Move your tokens clockwise around the board
5. Land on an opponent to **send them back home** 💥
6. Get all 4 tokens to the center to **win** 🏆

---

## ✨ Features

- 🟥🟩🟨🟦 **4 Players** — Red, Green, Yellow & Blue
- 🎲 **Animated Dice** — satisfying roll animation with real dot patterns
- 💥 **Token Capture** — land on opponents to send them back
- ⭐ **Safe Cells** — star-marked cells where tokens can't be captured
- 🔄 **Extra Turns** — rolling a 6, capturing, or reaching home earns a bonus turn
- 🏠 **Home Column** — colored path leading each token to the goal
- 🏆 **Win Screen** — confetti explosion when a player wins
- 📱 **No install** — single HTML file, works in any browser

---

## 🚀 Getting Started

### Option 1 — Just open it
```bash
# Clone the repo
git clone https://github.com/your-username/ludo-game.git

# Open in browser
open index.html
```

### Option 2 — Live Server (VS Code)
```
1. Install the Live Server extension in VS Code
2. Right-click index.html → "Open with Live Server"
```

### Option 3 — GitHub Pages
```
Settings → Pages → Source: main branch → / (root)
Your game is live at: https://your-username.github.io/ludo-game
```

---

## 📁 Project Structure

```
ludo-game/
├── index.html        # Everything — board, styles, game logic
└── screenshots/      # README screenshots (add your own)
    ├── board.png
    ├── win.png
    ├── turn.png
    └── select.png
```

> Single file project — all HTML, CSS and JS live in `index.html`

---

## 🎯 Game Rules

| Rule | Detail |
|---|---|
| **Enter board** | Must roll a 6 to move a token out of home |
| **Movement** | Tokens travel clockwise around the 52-cell ring |
| **Capture** | Landing on an opponent sends them back to home base |
| **Safe cells** | Marked with ⭐ — no captures allowed here |
| **Home column** | Last 5 cells before goal, only your color can enter |
| **Winning** | First to get all 4 tokens to the center wins |
| **Extra turn** | Rolling 6 / capturing / scoring a token home = roll again |

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| **HTML5** | Board structure & DOM layout |
| **CSS3** | Animations, gradients, responsive design |
| **Vanilla JS** | Complete game engine — turn logic, capture, win detection |
| **Google Fonts** | Baloo 2 + Poppins typography |

Zero dependencies. Zero build steps. Zero frameworks. Pure vibes. 🤙

---

## 🤝 Contributing

Feel free to fork and vibe-code your own improvements:

```bash
git fork https://github.com/your-username/ludo-game.git
git checkout -b feature/your-cool-idea
git commit -m "add: something cool"
git push origin feature/your-cool-idea
```

Ideas for improvements:
- [ ] Add sound effects 🔊
- [ ] Mobile / touch support 📱
- [ ] AI player mode 🤖
- [ ] Online multiplayer 🌐
- [ ] Token animation between cells ✨

---

## 📄 License

```
MIT License — free to use, fork, remix, and vibe with.
```

---

<div align="center">

Made with 🎲 and good vibes

⭐ **Star this repo if you had fun playing!**

</div>
