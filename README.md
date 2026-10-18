# PLAYGROUND.COM - Football Arcade World

A single-page football game site: arcade matches (1v1 to 11v11), mini games, tournaments,
career mode, player cards and packs, a market, a club with achievements, news, quiz and more.

It is plain HTML, CSS and JavaScript in one file (`index.html`). No build step, no dependencies.
Progress (coins, squad, shop, scores) is saved in the browser with localStorage.

## Run locally
Open `index.html` in a browser.

## Put it on GitHub
1. Create a new repository on github.com (for example `playground`).
2. Click **Add file > Upload files**, drag in everything from this folder
   (`index.html`, `vercel.json`, `README.md`, `.gitignore`) and click **Commit changes**.

## Connect it to Vercel
1. Go to vercel.com and sign in with GitHub.
2. Click **Add New > Project**, pick your `playground` repository and click **Import**.
3. Leave all settings as they are (Framework Preset: **Other**, no build command, no output directory)
   and click **Deploy**.
4. Every time you push a change to GitHub, Vercel redeploys automatically.

## Notes
- **Playground AI** and cloud **Feedback** use the claude.ai runtime. On your own domain they fall back
  gracefully: the AI tab says it is not available and feedback is saved on the device only.
  To get a live AI coach on your own site you would add a small server route that calls an AI API.
- Real club names are used for fun, as plain text and colours only (no logos or real players).

Created by Abir and Anshveer.
