# Mabati Rolling Mills Website

A premium, responsive corporate website for Mabati Rolling Mills, built with plain HTML, CSS and JavaScript so it can be deployed directly to GitHub Pages.

## Structure

- `index.html` — semantic page structure and content
- `styles.css` — responsive industrial corporate design
- `script.js` — mobile navigation, scroll reveals, active navigation and image fallbacks
- `assets/logo.svg` — lightweight MRM-inspired brand mark
- `.github/workflows/deploy.yml` — automatic GitHub Pages deployment

## Run locally

Open `index.html` in a browser, or serve the directory with any static web server.

## GitHub Pages

1. Push the project to the repository.
2. In GitHub, open **Settings → Pages**.
3. Set the source to **GitHub Actions** if it is not already selected.
4. Every push to `main` deploys the site through the included workflow.

The site uses relative local asset paths, so it works from a repository subpath such as `https://USERNAME.github.io/REPOSITORY/`.

## Images

The photography uses remote Unsplash image URLs for the initial design. The page includes graceful image-error handling so a failed image does not break the layout. Replace the URLs with licensed company photography before production launch.

## Contact placeholders

The phone, email and Nairobi address are placeholders supplied in the design brief. Replace them with verified company details before publishing.

## SEO/accessibility

The page includes a descriptive title, meta description, semantic landmarks, keyboard-accessible navigation, a skip link, descriptive image alt text and responsive layouts.
