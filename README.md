# jespasac.github.io

Personal site of Jordi Espasa — FinOps Director.

Built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages.

## Structure

```
_layouts/       # Page templates (default, post)
_includes/      # Reusable components (nav, footer)
_posts/         # Articles in Markdown (YYYY-MM-DD-title.md)
assets/css/     # Stylesheet
index.html      # Homepage
writing.html    # Article index
```

## Adding a new article

Create a file in `_posts/` with the format `YYYY-MM-DD-slug.md` and the following front matter:

```yaml
---
layout: post
title: "Your Article Title"
category: "Cloud Economics"
date: 2025-02-01
read_time: 5
excerpt: "One sentence summary shown in previews."
---

Your content in Markdown here.
```

Push to `main` — GitHub Pages compiles and publishes automatically.
