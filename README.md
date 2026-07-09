# Calculator App

A simple, working calculator built with HTML/CSS/JS on the frontend and a tiny Express server to serve it. Good second project for practicing the GitHub → Railway workflow.

## 1. Run it locally (optional)

```bash
npm install
npm start
```

Open http://localhost:3000 in your browser.

## 2. Push it to GitHub

1. Create a new empty repository on GitHub (no README/gitignore, you already have them here).
2. In this project folder:

```bash
git init
git add .
git commit -m "First commit - calculator"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

## 3. Deploy on Railway

1. Go to https://railway.app and sign in with GitHub.
2. Click **New Project** → **Deploy from GitHub repo**.
3. Select the repo you just pushed.
4. Railway auto-detects Node, installs dependencies, and runs `npm start`.
5. Under the service's Settings, click **Generate Domain** to get a public URL.

Visit your Railway URL to use the calculator live, from anywhere.

## 4. Ideas to extend it

- Add a history of past calculations
- Add a dark/light theme toggle
- Support keyboard shortcuts (already partially wired up in the JS)
- Add scientific functions (sin, cos, sqrt, etc.)

Whenever you make a change, just commit and push — Railway redeploys automatically.
