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

Output is written to `site/` and can be published to any static host (nginx, GitLab Pages, etc.).

## Screenshots

PNG files live in `docs/assets/screenshots/`. See that folder’s README for naming and placeholders.
