# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Academic personal website for Matthew Hockert, built with **Jekyll 3.9.5** on the **academicpages** template (forked from Minimal Mistakes theme). Hosted on **GitHub Pages** and auto-deployed from the `main` branch.

Live site: https://matthewhockert.github.io

## Build & Development Commands

```bash
# Install Ruby dependencies
bundle install

# Local dev server with live reload (primary command)
bundle exec jekyll liveserve

# Build static site (outputs to _site/)
bundle exec jekyll build

# Minify JavaScript (rarely needed, only when editing JS plugins)
npm run uglify
```

**Note:** `_config.yml` is NOT reloaded on live rebuild — restart the server after config changes.

## Architecture

This is a Jekyll static site. Content flows through: **Markdown/HTML files** → **Liquid templates** (`_layouts/` + `_includes/`) → **static HTML** in `_site/`.

### Content locations

- **`_pages/`** — Main site pages (about, publications, CV, blog, projects, flashcards, data)
- **`_posts/`** — Blog posts (named `YYYY-MM-DD-title.md`)
- **`_publications/`** — Academic publication entries
- **`files/`** — Downloadable assets (PDFs, Anki decks, datasets)
- **`images/`** — Site images including profile photo

### Template system

- **`_layouts/`** — Page templates: `default.html` (base) → `single.html` (standard page), `post.html`, `home.html`
- **`_includes/`** — Reusable components (header, footer, sidebar, author profile, SEO)
- **`_sass/`** — SCSS stylesheets; compiled to `assets/css/main.css`

### Configuration

- **`_config.yml`** — Site settings, author info, collections, plugin config, default layouts
- **`_config.dev.yml`** — Development overrides (localhost URL, expanded CSS)
- **`_data/navigation.yml`** — Top navigation menu links
- **`_data/ui-text.yml`** — UI string translations

### Collections (defined in `_config.yml`)

The site uses Jekyll collections for structured content: `posts` and `publications`. Each collection maps to a corresponding `_collectionname/` directory. Default front matter (layout, author profile visibility) is set per-collection in `_config.yml`.

### JavaScript

jQuery-based with plugins bundled into `assets/js/main.min.js`. Source plugins live in `assets/js/plugins/`. The `npm run uglify` script concatenates and minifies them.

- **`images/`** — Profile photo and favicon/manifest files only
