# teknikebana

A minimal blog built with Jekyll, hosted on GitHub Pages.

## Local development

```
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000/teknikebana/`.

## Adding a post

Create a file in `_posts/` named `YYYY-MM-DD-title-slug.md` with front matter:

```yaml
---
title: "Your Post Title"
date: YYYY-MM-DD
---

Post content in markdown here.
```

## Deployment

Push to `main`. GitHub Pages builds and deploys automatically.
