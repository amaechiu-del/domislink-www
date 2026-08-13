# domislink-www

A static landing page / PWA for DomisLink.

## Quick start

- Preview locally: open index.html in a browser.
- Optional (recommended): run a simple local static server to test PWA features:
  - Install a static server: npm i -g serve
  - Run: serve .

## Deployment

This repository is configured to deploy to GitHub Pages automatically on push to the default branch via GitHub Actions. The workflow publishes the repository root by default. If you later add a build step (e.g., a framework that outputs to ./dist), update the workflow to upload that folder instead.

## Development notes

- No package.json found: this looks like a plain static site. If you convert to a Node-based build (Vite/React/etc.), add package.json with scripts:
  - "build": "your-build-command"

## Contributing

1. Fork the repository.
2. Create a branch for your change: git checkout -b feat/something
3. Make changes, commit, and open a PR against the main branch.

## Next steps after merging

- Verify GitHub Pages settings under Settings → Pages and confirm the site is published.
- Add a LICENSE file if you want to open-source the project (MIT added in this branch by default).
- Optionally connect the repo to Vercel/Netlify for preview deploys.

