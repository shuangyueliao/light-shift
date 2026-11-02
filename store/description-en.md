# Light Shift — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

A glowing Lights Out puzzle. Tap a tile to flip it with its neighbours —
switch off the whole grid. Solvable levels, star ratings, endless mode,
one hint per board.

## Details

- Genre: Puzzle / Brain / Casual
- Controls: Mouse / Touch (tap a tile). Keyboard: arrows + Enter/Space to flip, H hint, M mute, R reshuffle.
- Features: 5x5 neon grid with wave-propagation flip animations, guaranteed
  solvable generated levels (Level N = 4+N random flips, limit 4+N), star
  ratings by move count, par display, pentatonic flip sounds mapped to tile
  coordinates, best level / fastest clear / endless records saved locally,
  single-file HTML5 (no external assets), works offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking.

## Tags
lights-out, puzzle, brain, casual, logic, neon, minimalist, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: cover-16x9.png (1280×720)
- [ ] Screenshots: screenshot-raw.png (1280×800)

## itch.io
- Upload light-shift-itch.zip, mark "This file is playable in browser",
  entry file: index.html, viewport 480×640, kind: html
- Pricing: $0 (donations optional)
