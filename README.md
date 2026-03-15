# Rooted — Website

This folder contains the static website for the Rooted app, intended for hosting on **GitHub Pages**.

## Pages

| File | Purpose |
|---|---|
| `index.html` | Landing page — hero, features, download links |
| `privacy.html` | Privacy policy (required for App Store / Play Store) |
| `support.html` | Support page with contact email and FAQ |
| `styles.css` | Shared stylesheet for all pages |

## Hosting (GitHub Pages)

1. Push this folder (or the whole repo) to GitHub.
2. Go to **Settings → Pages** in your repository.
3. Set the source to the branch and folder containing `web/`.
4. GitHub Pages will serve `index.html` at your Pages URL.

All pages are plain static HTML with no build step required. They work correctly when opened directly in a browser as local files.

## Design

The design matches the Rooted app visual language:

- **Colors:** warm cream background (`#F5F2EC`), soft green accent (`#5C7A5A`), pale green highlights (`#D4E8D3`)
- **Fonts:** Lora (headings, serif) + DM Sans (body, sans-serif) — loaded from Google Fonts
- **Tone:** calm, minimal, nature-inspired — no frameworks, no build tools

## Contact

Support email: rooted.app.help@gmail.com
