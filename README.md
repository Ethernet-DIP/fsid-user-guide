# FSID Staff Console Guide

Operator how-to documentation for the MoE admin console and institution portal.
Built with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

Engineering design notes live under `../docs/` and are separate from this guide.

## Local preview

```bash
cd user-guide
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
mkdocs serve
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Build static site

```bash
mkdocs build
```

Output is written to `site/`.

## GitHub Pages

Published site: [https://ethernet-dip.github.io/fsid-user-guide/](https://ethernet-dip.github.io/fsid-user-guide/)

Deploys automatically on every push to `main` via [`.github/workflows/deploy-docs.yml`](.github/workflows/deploy-docs.yml) (GitHub Actions → Pages).

Manual one-off from a laptop (legacy `gh-pages` branch):

```bash
mkdocs gh-deploy --force
```

## Screenshots

PNG files live in `docs/assets/screenshots/`. See that folder’s README for naming and placeholders.
