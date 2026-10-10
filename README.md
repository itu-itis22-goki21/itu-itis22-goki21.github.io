# App site

Static GitHub Pages site for my apps. No build step: plain HTML and one shared stylesheet.

```
index.html              Apps hub (one card per app)
assets/style.css        Shared styles
momentune/              Momentune: landing, privacy, terms, support
404.html
.nojekyll               Serve files as-is (skip Jekyll)
```

## Updating

When Momentune is live, replace the "Coming soon" badge in `momentune/index.html` with the App Store link (instructions are in the HTML comment there).

## Publish on GitHub Pages

The repo `itu-itis22-goki21/itu-itis22-goki21.github.io` publishes `main` automatically. Commit and push to update the site.

The site will be at `https://itu-itis22-goki21.github.io/`. URLs for App Store Connect:

| Field | URL |
| --- | --- |
| Privacy Policy URL | `https://itu-itis22-goki21.github.io/momentune/privacy.html` |
| Support URL | `https://itu-itis22-goki21.github.io/momentune/support.html` |
| Marketing URL | `https://itu-itis22-goki21.github.io/momentune/` |
| Terms of Use (EULA) | `https://itu-itis22-goki21.github.io/momentune/terms.html` |

## Adding another app

1. Copy the `momentune/` folder to `<new-app>/` and edit the text, the icon and the `--app-accent` colors in each page's `<style>` tag.
2. In `index.html`, copy the Momentune `<article class="app-card">` and update it.
