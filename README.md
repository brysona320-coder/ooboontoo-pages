# Ooboontoo Pages

Static Ubuntu-style terminal website for GitHub Pages.

## Publish

The website source must be committed as `index.html` at the repository root. The HTML is approximately 29 MB, so upload it with Git instead of GitHub's web uploader (25 MiB limit).

In a folder containing `index.html`, run:

```bash
git clone https://github.com/brysona320-coder/ooboontoo-pages.git
cp index.html ooboontoo-pages/index.html
cd ooboontoo-pages
git add index.html
git commit -m "Add Ooboontoo site"
git push origin main
```

In repository **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**. The included workflow publishes the site on every push to main.

Website: https://brysona320-coder.github.io/ooboontoo-pages/

GitHub Pages is static hosting: it can run the in-browser HTML/JavaScript interface, but it does not provide a real Ubuntu server.
