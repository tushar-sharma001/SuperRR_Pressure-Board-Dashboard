# The Pressure Board · SupeRR Selector S2

Interactive dashboard of the most reliable IPL/T20I batters and bowlers under pressure.
It is a single static page (`index.html`): plain HTML, CSS and JavaScript, with the data embedded.
No build step, no server, no dependencies. `data.json` is the same data, for reference.

## Run locally
Double-click `index.html`.

## Put it live on GitHub Pages
1. Create a new public repository on GitHub (e.g. `pressure-board`).
2. In this folder:
   git init
   git add .
   git commit -m "Pressure Board dashboard"
   git branch -M main
   git remote add origin https://github.com/tushar-sharma001/SuperRR_Pressure-Board-Dashboard.git
   git push -u origin main
3. On GitHub: Settings -> Pages -> Build and deployment -> Source: **GitHub Actions**.
4. Open the Actions tab; when "Deploy dashboard to GitHub Pages" turns green, the site is live at
   https://github.com/tushar-sharma001/SuperRR_Pressure-Board-Dashboard/
