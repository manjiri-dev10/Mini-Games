# 🎮 Mini Games Collection

A portfolio project featuring **4 fully playable browser games** built with pure HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies.

> Open any `.html` file directly in your browser and start playing.

---

## 🕹️ Games

### 🐍 Snake Game — `snake-game.html`
Classic snake with a modern twist. The snake speeds up as you level up, bonus food appears for extra points, and particle effects fire on every eat.

- **Controls:** Arrow keys or WASD
- **Scoring:** 10 pts × level per food; 50 pts × level for bonus food
- **Concepts:** Canvas 2D API, `requestAnimationFrame` game loop, collision detection, particle system, dynamic speed scaling

---

### 🧠 Quiz Arena — `quiz-app.html`
A 40-question trivia game across four categories with a countdown timer and detailed answer feedback.

- **Categories:** Science 🔬 · History 🏛️ · Technology 💻 · Geography 🌍
- **Difficulty levels:** Easy / Medium / Hard (affects question pool)
- **Concepts:** Data-driven UI, timer management, dynamic rendering, score tracking

---

### 🃏 Memory Match — `memory-game.html`
Flip cards to find matching emoji pairs. Three grid sizes to choose from, with a move counter, live timer, and best-score persistence.

- **Grid sizes:** Easy (4×4) · Medium (6×6) · Hard (8×8)
- **Tracks:** Moves, time elapsed, and personal best
- **Concepts:** State management, CSS 3D card flip animation, `localStorage` for best scores, event-driven UI

---

### ⭕ Tic Tac Toe — `tic-tac-toe.html`
Classic board game with an unbeatable AI and a persistent scoreboard.

- **Modes:** vs AI · 2-Player local
- **AI difficulty:** Easy (random) · Medium (mixed) · Unbeatable (full Minimax + alpha-beta pruning)
- **Concepts:** Minimax algorithm, alpha-beta pruning, win detection, session score tracking

---

## 📁 Project Structure

```
mini-games-collection/
├── index.html           ← Game hub / landing page
├── snake-game.html      ← Canvas-based arcade game
├── quiz-app.html        ← Data-driven trivia quiz
├── memory-game.html     ← Card matching game
└── tic-tac-toe.html     ← AI-powered board game
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and Canvas element |
| CSS3 | Animations, 3D transforms, responsive layouts |
| Vanilla JavaScript | All game logic, state, and interactivity |
| Canvas 2D API | Snake game rendering and particle effects |
| Minimax + Alpha-Beta | Tic Tac Toe AI |

---

## 💡 Skills Demonstrated

- **Game Loop** — `requestAnimationFrame` with delta timing for frame-rate-independent movement
- **AI (Minimax)** — Decision-tree search with alpha-beta pruning for optimal Tic Tac Toe play
- **State Management** — Clean game state transitions, resets, and multi-screen flows
- **Canvas 2D API** — Real-time drawing, compositing, and particle effects
- **Event Handling** — Keyboard, mouse, and touch input
- **Data Handling** — Dynamic question rendering, category filtering, and score computation
- **CSS Animation** — 3D card flips, glow effects, shake feedback, and entrance transitions

---

## 🚀 Getting Started

No installation required.

```bash
git clone https://github.com/manjiri-dev10/mini-games-collection.git
cd mini-games-collection
open index.html        # macOS
# or
start index.html       # Windows
# or just double-click index.html in your file explorer
```

---
