# Zobuddy 🐾

Your Zodiac Buddy Companion — build streaks, grow your power, and battle friends!

## How it works

This project auto-deploys to GitHub Pages whenever you push to `main`.

### Project structure
```
src/app.jsx        ← Your app source code (edit this!)
public/            ← Static assets (icons, manifest, service worker)
build.js           ← Build script (compiles JSX → plain JS)
.github/workflows/ ← GitHub Actions auto-build & deploy
```

### Your workflow
1. Edit `src/app.jsx` (your app code) or files in `public/`
2. Push to `main`
3. GitHub Actions automatically compiles and deploys
4. Your site updates at your GitHub Pages URL

### First-time setup
1. Push this entire project to your GitHub repo
2. Go to **Settings → Pages → Source** and select **GitHub Actions**
3. Push a commit — the workflow will build and deploy automatically

### Version info
- **v2.0.0** — Pre-compiled build (no more in-browser Babel)
  - Removed ~800KB Babel download for users
  - Faster load times on all devices
  - Fixes blank screen on Android phones
- **v1.x** — Original single-file with in-browser Babel compilation
