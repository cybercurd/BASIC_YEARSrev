# USMLE Step 1 — Hematology & Oncology Complete

This repository contains a static HTML website prepared for GitHub Pages.

## Files

- `index.html` — the main website file
- `.nojekyll` — tells GitHub Pages to serve the site as plain static HTML
- `README.md` — setup instructions

## How to publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** main
   - **Folder:** /root
5. Click **Save**.
6. Wait for GitHub Pages to publish the site. The public site URL will appear on the same Pages settings screen.

## Local preview

Open `index.html` directly in a browser, or run a simple local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```
