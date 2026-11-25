# WeightTracker

Small mobile-first, dark-themed weight tracker web app (home-screen capable on iPhone: apple-mobile-web-app meta tags, `apple-touch-icon.png`).

## Stack and files
- `index.html`: the whole app (HTML, CSS, JS inline). No package.json, build step or tests found.
- `apple-touch-icon.png`, `README.md` (just a title), `CNAME`: weight-tracker.tstoub.com.
- Git remote: github.com/tstoub77/Weight_Tracker.

## Run / deploy
- Run: open `index.html` in a browser (no launch.json entry).
- Deploy: Unknown — confirm with Tim. CNAME suggests GitHub Pages, not verified.

## Gotchas
- Commit history shows `index.html` was replaced wholesale a few times to fix errors; prefer editing in place.
- Data storage method (localStorage vs other) not verified. Unknown — confirm before changing anything that touches saved data.
