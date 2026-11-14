# Personal website

This is a minimal GitHub Pages site using Jekyll. Everything is hosted by GitHub, and there are no local setup steps.

## Publish an article

1. Open the **[_posts](_posts)** folder in GitHub.
2. Add a file named `YYYY-MM-DD-my-article.md` (for example `2026-11-14-first-post.md`).
3. Include this at the top of the file:

```markdown
---
layout: post
title: "My article title"
date: 2026-11-14
---

Write the article in Markdown here.
```

4. Commit the file to `main`. GitHub Pages automatically rebuilds the homepage, adds the article to the list, and creates its individual page at `/blog/my-article/`.

Posts are shown newest first. Use today's or a past date: Jekyll does not publish future-dated posts by default. File names must follow `YYYY-MM-DD-title.md`, and the YAML front matter (`---` lines) is required.

## Edit the site

- `index.html` — homepage bio and post listing
- `_layouts/post.html` — individual article layout
- `_layouts/default.html` — HTML shell
- `assets/css/style.css` — minimal styling
- `_config.yml` — Jekyll settings

If GitHub Pages is not enabled: **Settings → Pages → Deploy from a branch → main → /(root)**.

Site: https://kyle-askeland.github.io
