# Striver A2Z DSA Tracker

This workspace contains a static HTML dashboard for tracking DSA practice progress.

## Deploy status
- A deploy-ready entrypoint file is available as `index.html`.
- The original file `dsa_tracker.html` is also present and can be renamed or used directly.
- No git repository remote is configured in this workspace, so I could not publish it automatically from here.

## Run locally
### Option 1: Open directly
- Open `index.html` in your browser.

### Option 2: Local static server
From `c:\Users\ASUS\Desktop\a2z`:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to a static host
You can deploy the site to any static hosting service that supports a single `index.html` entrypoint, for example:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

Just upload the workspace files or connect a Git repository containing `index.html`.
