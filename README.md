# Personal website

A minimal GitHub Pages / Jekyll site. No local setup needed.

## Edit the homepage

Edit **[index.md](index.md)** directly in GitHub to change the bio or heading. The posts list below the bio is generated automatically by Jekyll—leave the Liquid code under `## Posts` in place.

## Publish an article

1. Open the **[_posts](_posts)** directory in GitHub.
2. Create a Markdown file named `YYYY-MM-DD-my-article.md`, for example `2026-11-14-first-post.md`.
3. Start it with:

```markdown
---
layout: post
title: "My article title"
date: 2026-11-14
---

Write the article in Markdown here.
```

4. Commit to `main`. GitHub Pages rebuilds the site, puts the new post on the homepage, and creates a page at `/blog/my-article/`.

Posts appear newest first. Future-dated posts are not published by default. Use filenames of the form `YYYY-MM-DD-title.md` and keep the YAML front matter.

## Other files

- `_layouts/post.html` — individual article page
- `_layouts/default.html` — shared HTML shell
- `assets/css/style.css` — shared styling for homepage and posts
- `_config.yml` — Jekyll settings

Enable GitHub Pages at **Settings → Pages → Deploy from a branch → main → /(root)** if it is not already enabled.

Site: https://kyle-askeland.github.io
