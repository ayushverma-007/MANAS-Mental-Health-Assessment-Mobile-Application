# MANAS — Mental Health Assessment Mobile Application

Version: 1.0.1

## Overview
MANAS is a client-side mental-health assessment demo built as a mobile-friendly web app. The UI is static HTML/CSS/JS located in the `manas-demo/` folder and includes pages for onboarding, assessments, profile, and results.

## What it does
- Provides guided mental-health surveys and wellness checks.
- Demonstrates a mobile-friendly assessment flow without a backend (demo only).
- Key pages: `index.html`, `login.html`, `registration.html`, `survey.html`, `profile.html`, `goalreached.html`, `wellnesscheck.html`.

## Project structure
- `manas-demo/` — main demo site (open `manas-demo/index.html` in a browser)

## User flow
1. Open `manas-demo/index.html` (home)
2. Login or register (`login.html` / `registration.html`)
3. Complete surveys (`survey.html`, `wellnesscheck.html`)
4. View results (`goalreached.html`, `growth.html`, `profile.html`)

## Screenshots
Place screenshots under `manas-demo/screenshots/` and reference them below. Example Markdown:

```md
![Home screen](manas-demo/screenshots/home.png)
![Survey screen](manas-demo/screenshots/survey.png)
```

If you want, I can add placeholder screenshots or help capture them from a running local server.

## How to run locally
Open `manas-demo/index.html` in a browser or serve the folder with a simple static server:

```bash
cd manas-demo
python -m http.server 8000
# open http://localhost:8000
```

## Changelog
- 1.0.1 — README: added Screenshots and Changelog (2026-08-13)
- 1.0.0 — Initial demo import: static HTML/CSS/JS pages

## GitHub push steps
From the project root (`manas-2.0`) — these are the commands I used previously to initialize and push the project:

```bash
git add .
git commit -m "Update README: add screenshots and changelog"
git push
```

Notes:
- If the remote uses `master` as default, replace `main` with `master` when needed.

## License & Credits
Add license information if required.

---
If you'd like, I can commit and push this README update for you now, and/or add placeholder screenshots.
