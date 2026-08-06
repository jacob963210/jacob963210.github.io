# Bloody Luck

A fictional gothic slot-machine prototype for entertainment only. No real-money wagering.

## Current build

- Version: v0.2
- Layout: 5 reels × 3 rows
- Paylines: 20 fixed lines
- Win direction: left to right, beginning on reel 1
- Betting: line bet × 20 active lines
- Symbols: Phantom Wild, Blood Scatter, Poison Vial, Skull, Bone Key, Lantern, Cursed Book, A, K, Q
- Features currently implemented: Wild substitution, scatter payouts, visible winning lines, Blood meter, Venom meter, paytable and line reference

## Hosting

GitHub is the source repository. Netlify should publish directly from the repository root using `netlify.toml`.

## Files

- `index.html` — interface
- `styles.css` — mobile-first presentation
- `app.js` — reels, paylines, bets, payouts and meters
- `netlify.toml` — Netlify deployment and cache headers

## Development note

The obsolete v1 service worker and manifest were removed because they could cause Safari to keep serving the old single-row prototype.
