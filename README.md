# Pedroza Printing — Website & Marketing Assets

## Local Preview

Open `index.html` in a browser. No build step needed.

Or serve locally:
```
python3 -m http.server 8080
```
Then open http://localhost:8080

## Deploy

Upload to any static host:
- **GitHub Pages:** Push to a repo, enable Pages in settings
- **Netlify:** Drag and drop the folder at app.netlify.com/drop
- **Cloudflare Pages:** Connect repo or direct upload

## Adding a Case Study

1. Add project photos to `assets/projects/`
2. Open `index.html`
3. Find the `<!-- CASE STUDIES -->` section
4. Copy an existing `<article class="case-study">` block
5. Update the title, description, bullets, and image `src`
6. Save and deploy

## Generating the One-Pager PDF

1. Open `one-pager.html` in Chrome
2. Print → Save as PDF
3. Settings: Letter size, no margins, background graphics ON

## Files

- `index.html` — Portfolio site (single page)
- `one-pager.html` — Capabilities one-pager (print to PDF)
- `copy/thomasnet.md` — Thomasnet listing copy (paste into profile)
- `copy/cold-emails.md` — 3 cold outreach email templates
- `copy/linkedin.md` — LinkedIn profile copy and post template
