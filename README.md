# ⛏ Digcraft

**Dig deep. Dodge fire. Find the jackpot.**

Digcraft is a browser mining game made in a single HTML file, with no libraries, no build step and no downloads. Open it and play on desktop (mouse and keyboard) or on your phone (touch).

▶ **Play it:** `https://YOUR-USERNAME.github.io/digcraft/`

---

## The story

Deep beneath the green fields of Digcraft Farm lies a legendary jackpot, buried by the very first farmers. Then came the drought. The crops withered and the farmer was running out of hope.

So he grabbed his trusty pickaxe, left his cosy house and began to dig through 100 layers of earth, past gleaming coins, sparkling diamonds and fire spirits awakened by his digging, to claim the jackpot at the very bottom and save the farm.

---

## Features

- **100 levels** that get bigger and harder, from a 5×5 grid up to 21×21. Level 1 starts unlocked, and winning a level unlocks the next.
- **Gravity digging:** dig below the farmer and he falls until he lands.
- **Treasure:** coins (+1, with 1–3 per box), diamonds (+5) and a hidden jackpot in the last row (+20, wins the level).
- **Chained boxes** that need **two hits** to break. They get more common deeper down.
- **Two kinds of fire**
  - *Still fire* stays in its box. If you fall into it, you lose a life.
  - *Moving fire* wakes up after a short delay (watch for the "!"), then floats after you through your tunnels. It obeys gravity, drops into holes you dig under it, and floats back up shafts to chase you. If it touches you, you lose a life.
- **3 lives** per game, and a home you can rest at for +1 life once per game.
- **The shop (Digcraft Market):**
  - Stackable tools: **Double Pick** (breaks 2 boxes in a row), **Fire Spotter** (reveals hidden fire for 5 seconds) and **Extinguisher** (puts out the nearest fire). Each use spends one.
  - 8 outfits: Farmer, Red Overalls, Green Thumb, Cowboy, Miner, Ninja, Wizard and Royal Digger.
- **A living farm:** a house with a smoking chimney, a fence, a tree, flowers, butterflies and a chicken you can tap for a golden egg (+2, up to 3 per game). The sky changes from day to sunset to night as the levels get harder.
- **Audio:** a menu theme and a faster in-game theme, plus sound effects for clicks, digging, chains, footsteps, coins, diamonds, fire, power-ups and more. Music and SFX can be muted separately. The sound is generated in the browser with the Web Audio API.
- **Progress is saved** in the browser (levels unlocked, coins, tools, outfits, high score).

---

## How to play

### Goal
Dig down to the jackpot in the last row without losing all 3 lives. Collect coins and diamonds on the way to spend in the shop.

### Keyboard / mouse

| Action | Control |
|---|---|
| Walk left / right | `←` `→` (or `A` `D`) |
| Step down | `↓` (or `S`) |
| Climb up a shaft | `↑` (or `W`) |
| Point at a box to break | `←` `→` `↓`, or move the mouse |
| Break the pointed box | **Click**, `Space` or `Enter` |
| Use Double Pick / Fire Spotter / Extinguisher | `1` / `2` / `3` |

### Touch
Tap a box beside the farmer to break it, tap an open space to walk, or use the on-screen buttons (⛏ ↑ ← ↓ →). Tap the chicken for an egg.

### Tips
- Dig a box under a moving fire's path and it will drop into the hole.
- Climbing up a shaft gets you away from moving fire.
- A box with chains needs two clicks: the first cracks the chain and the second breaks the box.
- Save coins for outfits and stock up on tools.

---

## Run it locally

No installation needed.

1. Download or clone this repo.
2. Open `index.html` in your browser by double-clicking it.

Or in **VS Code**: install the **Live Server** extension, right-click `index.html` and choose **Open with Live Server**.

To play on a phone, run Live Server and open the address it shows from a phone on the same Wi-Fi. Use your computer's local IP address in place of `127.0.0.1`.

## Host it free on GitHub Pages

1. Put the game file in the repo as `index.html`.
2. Go to **Settings → Pages**.
3. Under *Source*, pick **Deploy from a branch**, then choose `main` and `/ (root)` and click **Save**.
4. After a minute or two, the game is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

---

## Built with

- HTML5 `<canvas>` for all the graphics and UI
- Vanilla JavaScript, with no frameworks or libraries
- Web Audio API for the music and sound effects
- `localStorage` for saving progress

The whole game is in one file, so it's easy to read and change.

## Notes

- Progress is stored per browser and device, so there are no accounts or online leaderboards.
- Audio starts after your first click or key press, because browsers block sound until you interact with the page.

## License

Add the license you prefer here, for example MIT.
