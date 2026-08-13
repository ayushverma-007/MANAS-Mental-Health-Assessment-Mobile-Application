# MANAS — Mental Health Assessment Mobile Application

Version: 1.0.0

## Overview
MANAS is a simple client-side mental-health assessment demo built as a mobile-friendly web app. The UI is static HTML/CSS/JS located in the `manas-demo/` folder and includes pages for onboarding, assessments, profile, and results.

## What it does
- Provides guided mental-health surveys and wellness checks.
- Stores/provides assessment flow via static pages (no backend required for demo).
- Pages include: `index.html`, `login.html`, `registration.html`, `survey.html`, `profile.html`, `goalreached.html`, `wellnesscheck.html` and more under `manas-demo/`.

## Project structure

- `manas-demo/` — main demo site (open `manas-demo/index.html` in a browser)

## User flow
1. Open `manas-demo/index.html` (home)
2. Login or register (`login.html` / `registration.html`)
3. Complete surveys (`survey.html`, `wellnesscheck.html`)
4. View results (`goalreached.html`, `growth.html`, `profile.html`)

## How to run locally
1. Open the `manas-demo/index.html` file in your browser, or serve the folder via a simple static server.

Example (Python 3 built-in server):

```bash
cd manas-demo
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

## GitHub push steps
If your remote repository already exists (for example: https://github.com/ayushverma-007/MANAS-Mental-Health-Assessment-Mobile-Application), follow these commands from the project root (`manas-2.0`):

```bash
# initialize (if not already a git repo)
git init

# add files and commit
git add .
git commit -m "Initial import: MANAS demo"

# ensure the branch name is 'main' locally
git branch -M main

# add remote (replace URL if needed)
git remote add origin https://github.com/ayushverma-007/MANAS-Mental-Health-Assessment-Mobile-Application.git

# fetch remote and merge remote README if it exists (handles unrelated histories)
git fetch origin
# try pulling 'main', if remote's default branch is 'master' use that instead
git pull origin main --allow-unrelated-histories

# resolve any merge conflicts, then:
git add .
git commit -m "Merge remote README"

# push to GitHub
git push -u origin main
```

Notes:
- If the remote uses `master` as the default branch, replace `main` with `master` in `git pull` and `git push` commands.
- If you get merge conflicts after the pull, resolve them in your editor, then `git add` and `git commit` before pushing.

## License & Credits
Add license information if required.

---
Updated README with app summary and push instructions.
