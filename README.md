# gedit2_web

This repository hosts the standalone Docusaurus site for GEditBench v2.

## Requirements

- Node.js `>=20`
- npm

## Installation

```bash
npm ci
```

## Local Development

```bash
npm start
```

## Production Build

```bash
npm run build
```

The static site is generated into `build/`.

## Deployment

GitHub Pages deployment is handled by the workflow in `.github/workflows/deploy-pages.yml`.
Pushes to `main` rebuild and deploy the site to the `gedit2_web` project page.
