# Solitaire (for Grandma)

Classic Klondike solitaire. One file, no dependencies, no ads, no setup. Works on
phone, tablet, and computer in any browser. Just open the page and play.

## What's inside

- `index.html` — the whole game. That's it.

## Features

- Tap a card — if there's an obvious legal spot, it auto-moves there (fewer steps). Drag or tap-to-select still works when you want control.
- Double-tap a card to send it straight to the home piles.
- Tap the deck (now top-right) to deal. Tap again to recycle when it's empty. (Right side so right-handed players don't cover the board reaching across.)
- **New Game**, **Undo**, timer, and move counter up top.
- Gear menu (⚙): Draw 1 / Draw 3, **Hint**, **Auto-finish**, **Restart this deal**, **How to play**.
- ? button opens full instructions + "Deal a practice hand" (starts a game and immediately shows a pulsing hint so you can learn by following moves).
- Remembers your game if she closes the tab and comes back.
- Big, high-contrast cards that resize to fit any screen.
- **Make it yours** (gear menu ⚙):
  - **Card size** slider — enlarge the cards to whatever's comfortable; the board scrolls so nothing is lost. Great for older eyes.
  - **Table** colour — Emerald, Ocean, Midnight, Burgundy, Plum.
  - **Card back** design — Classic blue, Crimson, Forest, Slate, Royal plum.
  - **Card style** — Classic, Pips (traditional pip layout with hand-drawn King/Queen/Jack court cards), Large print, and Four-color suits.
  - Every choice is remembered between visits.
- A little celebration when she wins.

## Try it locally

Just double-click `index.html` to open it in a browser. Done.

(Or serve it: `python3 -m http.server` from this folder, then visit
`http://localhost:8000`.)

## Put it online (GitHub Pages — free)

1. Create a new GitHub repo, e.g. `grandma-solitaire`.
2. Upload `index.html` to the root of that repo (and this README if you like).
3. Repo **Settings → Pages → Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** / folder: **/ (root)** → Save.
4. Wait ~1 minute. Her game lives at:
   `https://<your-username>.github.io/grandma-solitaire/`
5. Send her that link. Tell her to "Add to Home Screen" so it opens like an app.

To change anything later, edit `index.html`, commit, and Pages redeploys itself.
