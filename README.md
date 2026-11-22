# The Stanley Button

A tiny narrator-driven browser game: follow absurd button rules, keep track of special instructions, and disappoint the narrator as slowly as possible.

## Play

- Open `index.html` locally in a browser, or
- Host it with GitHub Pages (repo is ready for Pages from the root).

## Gameplay

- Press the button according to the current instruction.
- Some rounds give **special instructions** that keep applying later. The narrator will not remind you.
- Rounds get harder/faster over time.
- 3 strikes = game over.
- Spend score in the **Shop** for expensive boosts.

## Controls

- **Mouse / touch**: click the button and menu UI
- **Space / Enter**: press the button
- **Esc**: open/close menu

## Features

- Rule-based rounds (counting, timing, patience, listening, label/signal tricks)
- Lingering special instructions (ambient conditions you must remember)
- In-game menu: Main / Shop / Settings / Credits
- Narrator TTS toggle + voice picker (browser `speechSynthesis`)
- Score shop: shields, strike repair, time dilator, score doubler, streak lock, narrator clarity

## Run locally

No build step. Just clone and open:

```bash
git clone https://github.com/iluxz/the-stanley-button.git
cd the-stanley-button
# open index.html in your browser
```

## Project files

- `index.html` - main game (GitHub Pages entrypoint)
- `stanley-button.html` - same game file (convenience copy)
- `README.md` - this file
- `LICENSE` - MIT

## Notes

- Voice options depend on voices installed/available in your browser/OS.
- This is a small single-file web game; no dependencies, no bundler.
