# Kyle Askeland — personal site

A lightweight portfolio and technical blog, hosted with GitHub Pages and Jekyll. No local setup required.

## Publishing a blog post

1. In the GitHub web interface, make a new branch.
2. Create a Markdown file in `_posts/` named `YYYY-MM-DD-your-post-title.md`.
3. Start the file with front matter, then write Markdown:

```markdown
---
layout: post
title: "Your article title"
description: "One sentence about the article."
date: 2026-11-11
---

Your article starts here.
```

4. Open a pull request targeting `main`.
5. Merge when ready. GitHub Pages builds and publishes posts from `main` automatically.

The blog list on `/blog/` updates automatically. No article is published until its file is merged into `main`. Dates should not be in the future relative to the build time.

## Website pages

- `index.md`: homepage
- `about/index.md`: About
- `projects/index.md`: Projects
- `blog/index.html`: blog listing
- `_layouts/`: site and post templates
- `assets/css/style.css`: styling

## GitHub Pages settings

In **Settings → Pages**, choose **Deploy from a branch**, **main**, and **/(root)**. Jekyll is built by GitHub Pages. The resulting site is https://kyle-askeland.github.io.

This site uses standard Jekyll without third-party themes or plugins. Layouts and styling can be edited directly in GitHub.
