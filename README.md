# Foran Games

A small, static collection of browser games hosted with GitHub Pages.

## Play locally

Serve the repository root with a local web server, then open its URL in a browser. The Catchphrase game loads its word categories from a JSON file, which requires HTTP (opening the HTML file directly won't load it).

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the site when changes are pushed to `main` and can also be started manually. In the repository's **Settings → Pages**, set the build and deployment source to **GitHub Actions**.

Add future games under `games/<game-name>/` and link to them from `index.html`.
