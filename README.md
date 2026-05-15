# flip7-calc

Single-file Flip7 card grid and simple next-card recommendation.

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

- Shows a fixed grid of all standard Flip7 cards (number, special, and action cards)
- Lets you track cards played with per-card `+1` / `-1`
- Lets you mark number draws to hand with `+hand`
- Shows a single simple recommendation for race-to-200 play
- Persists state in localStorage
