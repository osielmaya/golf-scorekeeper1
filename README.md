# Potrero Golf Course — 9-Hole Scorekeeper (Auto-refresh, Teams, Keypad)
- Auto-refresh: app reloads itself when a new version is published
- Scorecard Mode: Individuals or Teams (also synced on Leaderboard)
- Keypad 1–15 for fast scoring
- Preloaded players: Eric, Luz, Osiel, Francisco, Javier, Rafael (you can still add more)
- Teams tab, Courses tab, Past rounds, CSV export
- Installable PWA, offline ready

## Deploy to GitHub Pages (repo `golf-scorekeeper1`)
1. Upload these files at the repo **root**:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - icon-192.png
   - icon-512.png
   - apple-touch-icon.png
   - README.md
2. Settings → Pages → Source: `main` → `/ (root)` → Save
3. Open: https://osielmaya.github.io/golf-scorekeeper1/
