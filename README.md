# String Compare Challenge

A browser-based mini-game that tests your ability to spot character-level differences between two random strings. Speed and accuracy both count toward your final grade.

## How to Play

1. Open `index.html` in any modern browser — no build step required.
2. Use the slider to choose how many questions you want (10–50).
3. Click **Start Challenge**.
4. Two strings are displayed side by side. Count how many character positions differ between them and select the correct answer.
5. After each answer, a step-by-step solution panel reveals every deviation with position numbers and character-level diffs.
6. At the end, you receive a letter grade (A–F) with a full question breakdown.

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `A` `B` `C` `D` `E` | Select answer option |
| `Enter` / `Space` | Next question (after answering) |
| `Enter` / `Space` | Start game (on start screen) |

## Features

- Strings of random length (12–24 characters) with 0–4 intentional deviations per question
- Per-question timer displayed live; total and average time shown in results
- Animated character grid in the solution panel highlights matches and mismatches
- Letter grade (A/B/C/D/F) with score, accuracy %, average time, and per-question breakdown
- Fully responsive — works on mobile and desktop
- Keyboard-navigable with `prefers-reduced-motion` support

## Tech Stack

- Vanilla HTML, CSS, and JavaScript — zero dependencies, zero build tools
- Fonts: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (UI) · [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (strings/code)
- Icons: [Font Awesome 6](https://fontawesome.com/)

## Running Locally

```bash
# Clone the repo
git clone https://github.com/your-username/string-compare-mini-game-demo.git
cd string-compare-mini-game-demo

# Open in browser (macOS)
open index.html
```

No server, no dependencies, no install step.
