# flip7-calc

Single-file Flip7 next-card probability calculator.

## Run

Open `index.html` in a browser.

## What it does

- Tracks cards already played
- Tracks which played cards are in your hand
- Computes:
  - safe-draw probability
  - bust probability
  - draw/stop recommendation from a configurable threshold
- Persists state in localStorage
- Supports undo last card and full reset

## Notes

- Deck setup is editable (`label,count` per line), so you can match your Flip7 edition/rules.
