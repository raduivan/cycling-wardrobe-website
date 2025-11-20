# Cycling Wardrobe site

This folder contains the static pages used for GitHub Pages / Netlify.

## Local preview

You can open any of the HTML files directly in a browser, or serve them with a minimal HTTP server:

```bash
cd website
npx serve .
```

## Deploy to GitHub Pages

1. Commit this folder to the `gh-pages` branch or configure it as the root for Pages.
2. In GitHub → Settings → Pages, pick the branch & folder (e.g. `main` / `website`).
3. After Pages builds, the site will be live at `https://<user>.github.io/cycling-wardrobe/`.

## Custom domain

If you have `cyclingwardrobe.app`, create a CNAME record pointing to the GitHub Pages host and add a `CNAME` file here with the domain.
