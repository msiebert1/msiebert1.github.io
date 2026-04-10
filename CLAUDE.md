# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a personal academic website for Matthew R. Siebert (STScI Fellow / astrophysicist), built with Jekyll using the [academicpages](https://github.com/academicpages/academicpages.github.io) theme (a fork of Minimal Mistakes). It is deployed via GitHub Pages at `https://msiebert1.github.io`.

## Development Commands

```bash
# Install dependencies
bundle install

# Serve locally (standard)
bundle exec jekyll serve

# Serve locally with dev config (disables analytics, uses localhost URL)
bundle exec jekyll serve --config _config.yml,_config.dev.yml

# Live-reload via hawkins gem
bundle exec jekyll liveserve
```

The `_config.dev.yml` override sets `url: http://localhost:4000` and disables analytics — use it during local development to avoid polluting analytics.

## Site Architecture

### Content Collections
- `_pages/` — standalone pages (about/home, science, kaepora, etc.). The `about.md` serves as the site root (`permalink: /`).
- `_posts/` — blog posts (not prominently linked)
- `_portfolio/` — portfolio items (collection enabled, output: true)
- `_teaching/` — teaching items (collection enabled, output: true)
- `_drafts/` — unpublished drafts

### Navigation
Defined in `_data/navigation.yml`. The main nav currently links only to `/science/` and `/kaepora/`.

### Layouts & Includes
- `_layouts/` — page templates (single, archive, splash, default, talk, compress)
- `_includes/` — reusable partials (author-profile, masthead, sidebar, head, scripts, SEO, etc.)
- `_sass/` — SCSS stylesheets (compiled/compressed via `sass: style: compressed`)

### Static Assets
- `images/` — figures and photos referenced by pages
- `files/` — PDFs (papers, CV) and data files (tarballs) linked from content pages
- `assets/` — JS/CSS assets including the manifest

### Key Configuration (`_config.yml`)
- Theme: `jekyll-theme-midnight` (but note the academicpages theme overrides most styling via `_sass/` and `_includes/`)
- Active plugins: `jekyll-paginate`, `jekyll-gist`, `jekyll-redirect-from`, `jekyll-feed`, `jekyll-sitemap`
- Collections `talks` and `publications` are commented out (not currently active)
- `future: true` allows posts with future dates to be published

### Page Frontmatter Defaults
- All `_pages` get `layout: single, author_profile: true`
- All `_posts` get `layout: single, author_profile: true, read_time: true, comments: true`

## Content Patterns

Pages like `science.md` and `kaepora.md` mix Markdown with inline HTML/CSS for image thumbnails using the `.thumb` CSS class pattern (border, hover shadow, fixed height). Images link to full-resolution PDFs via `<a target="_blank">` wrappers.

The site's primary scientific content pages are:
- `/science/` — research highlights with figures linking to papers
- `/kaepora/` — documentation for the Kaepora SN Ia spectral database tool
