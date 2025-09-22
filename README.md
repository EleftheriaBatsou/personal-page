# Eleftheria Batsou — Personal Site

A modern, simple one-page site for Eleftheria Batsou, Developer Advocate at Cosine.  
Built with plain HTML/CSS, responsive, and optimized for GitHub Pages.

Live preview (Cosine deploy):
- https://bpauwdsh2igk.cosine.page

## Features
- Sticky, collapsing navigation on scroll
- Hero section with avatar, role, social links, and actions
- Sections: About, Work, Speaking (with upcoming events), Writing, Projects, Contact
- Minimal JS for header behavior and current year

## Structure
- `docs/index.html` — main page for GitHub Pages
- `docs/styles.css` — styles
- `site/` — original working files (mirrors of `docs/`)

## Deploy to GitHub Pages
1. Create a new GitHub repository (e.g., `eleftheria-personal-site`).
2. Push these files to the `main` branch.
3. In your repo: Settings → Pages:
   - Source: “Deploy from a branch”
   - Branch: `main`
   - Folder: `/docs`
4. GitHub Pages will publish your site at:
   - `https://<your-username>.github.io/<repo-name>/`

Optional:
- Add a `CNAME` file in `docs/` with your custom domain to use a custom URL.

## Edit content
- Update hero copy, links, and upcoming events in `docs/index.html`.
- Update colors or spacing in `docs/styles.css`.

## Credits
- Made with care — Cosine (https://cosine.sh)