# Wedding Site

A static, single-page wedding website template (photos, gallery, and an envelope-opening video). Built as plain HTML/CSS/JS — no build step required.

## Structure

- `index.html` — the site. Couple details, event info, and photo/video paths are configured near the top of the file in a `SITE_CONFIG` object.
- `images/` — photos used by the site (hero, gallery, event cards, dress code, etc).
- `videos/` — the envelope-opening intro video (`seal-open.mp4`).

## Customizing

Edit the `SITE_CONFIG` object at the top of `index.html` to change names, dates, venue/RSVP details, and photo paths. See the comments inside the file for field-by-field guidance.

## Deploying

This is a static site, so it can be hosted anywhere that serves static files:

- **GitHub Pages**: enable Pages for this repo (Settings → Pages → Deploy from branch → `main` / root), then the site will be live at `https://luvchakra.github.io/wedding-site/`.
- **Netlify / Vercel**: drag-and-drop the folder, or connect this repo — no build command needed, publish directory is the repo root.
