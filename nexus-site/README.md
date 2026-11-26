# Nexus Sequence Labs — Starter Site

Dark, high-contrast black + gold research site matching the emblem.

## Structure
- `index.html` — Home page with hero + disclaimer
- `css/styles.css` — Black/gold theme
- `assets/logo.png` — Emblem
- `admin/` — Decap CMS (visit `/admin` after deploy)
- `content/posts/` — Markdown articles

## Deploy to Netlify (recommended)
1. Push this folder to a GitHub repo.
2. Connect the repo to Netlify.
3. Build command: leave blank (static) or add a simple build step later.
4. Publish directory: `/` (root of this folder).
5. Add your domain in Netlify site settings and point DNS.
6. Enable Identity + Git Gateway in Netlify for Decap CMS login.

## Next steps
- Add more pages (about, compliance, research index).
- Wire a simple static site generator or keep pure HTML + JS to list posts.
- Hook your bot pipeline to commit new markdown into `content/posts/`.

Theme locked: pure black background, metallic gold accents, high contrast, clean lab aesthetic.
