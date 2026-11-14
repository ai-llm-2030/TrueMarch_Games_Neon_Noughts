# Neon Noughts

**Twenty neon rivals, nine-board Ultimate, fading marks and gravity. Out-think the Gridmaster.**

<p align="center">
  <img src="assets/screenshot-title.png" alt="Neon Noughts — title screen" width="820">
</p>

<p align="center">
  <a href="https://ai-llm-2030.github.io/TrueMarch_Games_Neon_Noughts/"><b>▶ Play Neon Noughts in your browser</b></a>
</p>

## What's new: Puzzle Forge

Build your own "win in N" puzzle and send it to a friend. Paint ✕ and ○ marks on a 5×5 board (four in a row wins). A built-in solver checks every reply ○ could make and proves the shortest forced win for ✕: 1, 2 or 3 moves, and how many first moves work. Each proven board gets a short share code such as `NN3-5T5R2WY9X`. Anyone can paste the code and play the puzzle against a defender that refutes every slip. Codes are proved again when they load, so a hand-edited code cannot claim a win that isn't there. Your puzzles and solves stay in local storage.

**Try it:** title screen → **Puzzle Forge**. Click a square (or **← ↑ ↓ →** + **Space**) to paint with the brush · **X** / **O** place · **Del** erase · **B** switch brush · **C** copy the code · **L** paste a code · **Enter** play it · **Esc** back. On touch, tap squares and use the buttons. **Remix today's daily** puts the daily puzzle on the board for you to edit.

<p align="center">
  <img src="assets/screenshot-forge.png" alt="Neon Noughts — Puzzle Forge editor with a proven win in 3" width="820">
</p>

## Gameplay

<p align="center">
  <img src="assets/screenshot-play.png" alt="Neon Noughts — gameplay" width="820">
</p>

## More screenshots

<table>
<tr><td width="50%"><img src="assets/screenshot-map.png" alt="The Rival Ladder"><br><sub>The Rival Ladder</sub></td><td width="50%"><img src="assets/screenshot-brief.png" alt="Meeting a rival"><br><sub>Meeting a rival</sub></td></tr>
<tr><td width="50%"><img src="assets/screenshot-play-ladder.png" alt="Victory"><br><sub>Victory</sub></td><td width="50%"><img src="assets/screenshot-shop.png" alt="The Spark Counter: marks and glows"><br><sub>The Spark Counter: marks and glows</sub></td></tr>
</table>

## Controls

| Keys | Action |
|---|---|
| Click, or ← ↑ ↓ → then Enter | Place your mark |
| 1 – 9 | Pick a square |
| H | Hint |
| U | Undo |
| Esc | Menu · back |
| P | Pause |
| M | Mute |

## Run it yourself

No install, no build step, no server code, no network. The game runs entirely in your browser and keeps your progress in the browser's local storage.

```bash
git clone https://github.com/ai-llm-2030/TrueMarch_Games_Neon_Noughts.git
cd TrueMarch_Games_Neon_Noughts
python3 -m http.server 8000
# open http://localhost:8000
```

Opening `index.html` directly works too in most browsers; a local server is the most reliable way.

## What's inside

```
TrueMarch_Games_Neon_Noughts/
├── index.html        the whole game: one file, plain JavaScript and <canvas>
├── lib/
│   ├── arcade.js     shared helpers: crisp canvas, frame loop, input, theme
│   └── arcade.css    shared look
├── assets/           the pictures in this README
├── LICENSE
└── README.md
```

Written from scratch in vanilla JavaScript: every sprite, background and sound is drawn or synthesised in code (Canvas 2D and the Web Audio API). No libraries, no frameworks, no third-party assets.

## About

**Neon Noughts** is one of the 120+ games made by **[TrueMarch](https://truemarch.com)**. This repository is the standalone single-player edition of the game.

## License

© 2026 TrueMarch. All rights reserved. The source is published so you can read it, learn from it and play the game; see [LICENSE](LICENSE).
