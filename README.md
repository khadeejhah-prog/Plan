# Body Tea 150

My 150-day glow-up tracker: workouts, food, skin, hair, cycle and progress.
It's a single web page with no build step: Vercel just serves the files.

## Put it online (GitHub + Vercel)

1. **GitHub:** New repository → name it `body-tea-150` → choose **Private** → Create.
   Then **uploading an existing file** → drag in everything from this folder → **Commit changes**.
2. **Vercel:** Sign in with GitHub → **Add New… → Project** → pick `body-tea-150` → **Import**.
   Framework preset: **Other**. Leave build and output settings empty → **Deploy**.
3. Open the `….vercel.app` link on your phone → **Add to Home Screen**.
   Open it from the icon, then Goals & plan → **Choose backup file** → Restore.

## Updating

Replace `index.html` in GitHub (Add file → Upload files) and commit.
Vercel redeploys by itself in about a minute. If you change `index.html`,
also bump `VERSION` in `sw.js` (e.g. `bt150-v8`) so phones pick up the new version.

## Your data

Ticks, food, logs and photos are saved **only in the phone's browser**, never in this repo.
Download a backup from Goals & plan every week or two. Never commit backup files here.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `sw.js` | Makes it work offline |
| `manifest.webmanifest`, `icon-*.png` | Home-screen app name and icon |
| `vercel.json` | Caching rules so updates show up, and keeps it out of Google |
| `robots.txt` | Keeps search engines out |
