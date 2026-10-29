# Kesion Journal

An independent English-language blog about AI, digital products, and creative work.

- Website: https://kesiondu.github.io/
- Projects: https://trendvido.com/ and https://flyingcar-ai.app/
- Built with Jekyll on GitHub Pages.

## Publish an article

Create `_posts/YYYY-MM-DD-english-slug.md` with YAML front matter:

```yaml
---
title: Article title
description: A concise summary.
category: Creative Practice
lang: en
---
```

Write the article in Markdown and commit it to `main`. GitHub Pages publishes changes automatically. Use a publication date no later than the current site date. Keep all public content and metadata in English.

## Site structure

- `_config.yml`: Site title, description, language, and URL.
- `index.html`: Homepage and article archive.
- `projects.md`: Project descriptions and links.
- `assets/style.css`: Responsive styles.
- `_layouts/`: Page templates.

Configure Settings → Pages to deploy from the root of `main`. Jekyll generates canonical URLs, a sitemap, and an RSS feed. Keep the Google Search Console verification file in the repository root.

A successful deployment does not guarantee search indexing or rankings.
