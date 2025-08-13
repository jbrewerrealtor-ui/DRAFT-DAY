# 2025 Fantasy Football Draft Board (Local Save)
Single‑file web app for 10‑team PPR drafts. Works great on iPad. No login, no backend — uses localStorage.

## Quick Start (GitHub Pages)
1. Create a new GitHub repo (public or private).
2. Upload everything in this folder to the repo (index.html, /data, /assets).
3. In the repo, go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick the default branch, folder `/ (root)`, and save.
4. Copy your public URL and open it on your iPad.

## Customize
- **Rankings:** Replace `data/sample_rankings.csv` (columns: rank,player,pos,team,bye). Or paste CSV/JSON directly in the app (**Settings** tab → Load).
- **Sleepers:** Edit `data/sleepers.json` or manage in the app.
- **Strategy:** Edit `data/strategy.html` to change the sheet.
- **Scoring Rules Image:** Add your image at `assets/scoring-rules.png` — it appears in the collapsible section at the top.

## Local Save
All drafted states, notes, sleepers, and settings are stored locally on each device via `localStorage
