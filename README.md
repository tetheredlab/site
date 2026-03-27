# Tethered Lab

Small Jekyll site for publishing a single stream of posts plus a few static pages.

## Structure

- `_posts/`: dated blog posts shown on the home page
- `_layouts/`: shared page templates
- `assets/main.scss`: single stylesheet entrypoint
- `about.md`, `contact.md`: static pages linked in site navigation
- `_config.yml`: Jekyll config, plugins, pagination, and nav settings

## Local Development

1. Use the Ruby version from `.ruby-version`.
2. Install dependencies with `bundle install`.
3. Start the site with `bundle exec jekyll serve`.
4. Open `http://127.0.0.1:4000`.

## Notes

- The homepage renders posts as a feed of excerpts.
- Navigation is controlled by `nav_pages` in `_config.yml`.

## Adding Posts

Add a markdown file to `_posts/` using the filename format `YYYY-MM-DD-title-slug.md`.

Example:

```md
---
layout: post
title: "New Post"
date: 2026-03-27
---

Post content goes here.
```
