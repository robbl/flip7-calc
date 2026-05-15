# flip7-calc

Single-file Flip7 next-card probability calculator.

## Run

Open `index.html` in a browser.

## Publish to GitHub Pages (main branch)

1. In GitHub, go to **Settings → Pages**.
2. Under **Build and deployment**, set:
   - **Source**: **Deploy from a branch**
   - **Branch**: **main**
   - **Folder**: **/ (root)**
3. Save, then after GitHub publishes, your site will be available at:
   - `https://<username>.github.io/<repository-name>/`
   - Example for this repo: `https://robbl.github.io/flip7-calc/`

## What it does

- Tracks cards already played
- Tracks which played cards are in your hand
- Provides a card grid with per-card `+1` / `-1` controls
- For number cards `0-12`, provides `+hand` to mark draws to your hand
- Computes:
  - safe-draw probability
  - bust probability
  - draw/stop recommendation from a configurable threshold
- Persists state in localStorage
- Supports undo last card and full reset

## Notes

- Deck setup is editable (`label,count` per line), so you can match your Flip7 edition/rules.
