# Inazira Skin Care

Jekyll blog for **skincare.inazira.com**, part of the INAZIRA site family.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000`.

## Adding a new post

Create a file in `_posts/` named `YYYY-MM-DD-title.md`:

```markdown
---
title: "Your Post Title"
date: 2026-09-01 10:00:00 +0600
---

Post content in Markdown goes here.
```

## Deployment

This repo is set up for **GitHub Pages**:

1. Push to the `main` branch of this repo.
2. In the repo's **Settings → Pages**, set source to `main` branch, `/ (root)`.
3. The `CNAME` file already points Pages at `skincare.inazira.com`.
4. At your domain DNS provider, add a **CNAME record**:
   - Host: `skincare`
   - Value: `<your-github-username>.github.io`
5. Wait for DNS to propagate (up to a few hours), then enable **Enforce HTTPS** in the Pages settings once GitHub shows the domain as verified.