# yunhenk.github.io

Personal GitHub Pages site built with Jekyll and the Minimal Mistakes theme.

The site has two sections:

- **Writing** — `/writing/`
- **Programming** — `/programming/`

The homepage is defined in `_pages/about.md`. Navigation is defined in `_data/navigation.yml`.

## Add a post

Create a Markdown file in `_posts/` using the `YYYY-MM-DD-title.md` naming convention:

```yaml
---
title: "Post title"
date: 2026-11-02
categories: writing
excerpt: "A short summary shown on the section page."
---

Post content goes here.
```

Use `categories: programming` for a programming post. A post can belong to both sections:

```yaml
categories:
  - writing
  - programming
```

## Project structure

- `_pages/about.md` — homepage with the two section cards
- `_pages/writing.md` — writing archive
- `_pages/programming.md` — programming archive
- `_posts/` — published posts
- `_data/navigation.yml` — top navigation
- `_config.yml` — site configuration
- `assets/css/custom.css` — homepage section card styling

## Local preview

```bash
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Then open `http://localhost:4000`.

## Deployment

Commit and push to the `master` branch. GitHub Pages will rebuild the site automatically.
