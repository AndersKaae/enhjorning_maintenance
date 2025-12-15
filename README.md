# Enhjorning Maintenance Page

A lightweight, static “under maintenance” page ready for GitHub Pages. Everything is self-contained: just HTML and CSS, no build step or extra assets.

## Usage

1. Update the content in `index.html` as needed:
   - The support email (`mailto:support@example.com`)
   - The status link (`https://status.example.com`)
   - The maintenance window times and wording
2. Commit and push to the branch you publish with GitHub Pages (commonly `main` with Pages set to `/` or `/docs`).
3. Verify the published page loads correctly at your Pages URL.

## Local preview

Open `index.html` directly in a browser, or serve the folder with any static server, e.g.:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
