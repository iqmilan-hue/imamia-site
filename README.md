# Imamia Milano — Website

Static one-page site for imamiamilano.org, deployed on Netlify.

## Structure
- `index.html` — homepage (hero, about, events, contact)
- `files/` — downloadable files (calendars, flyers, PDFs)
- `images/` — photos, logos, banners

## How to update
1. Edit `index.html` (or add new files) locally, or directly in GitHub's web editor.
2. Commit and push to `main`.
3. Netlify auto-deploys the new version within ~1 minute — no manual upload needed.

## Adding an event
Copy one `<div class="event">...</div>` block inside `index.html`, update the date/title/description.

## Adding a downloadable file
Place it in `files/`, then link to it: `<a href="files/yourfile.pdf" download>Download</a>`
