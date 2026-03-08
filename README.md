# ihybrd.github.io

Personal technical blog built with GitHub Pages + Jekyll.

Live site: `https://ihybrd.github.io/`

## Overview

This repository hosts my personal engineering notes and project write-ups.
The blog is focused on practical topics such as:

- coding experiments
- tooling and workflow notes
- project-specific technical walkthroughs

## Tech Stack

- GitHub Pages
- Jekyll
- Minima theme (`remote_theme: jekyll/minima`)

## Repository Structure

- `_posts/`: blog posts in Markdown
- `_layouts/`: custom page templates
- `images/`: static assets used by posts
- `_config.yml`: Jekyll site configuration
- `about.md`: about page shown in navigation

## Writing a New Post

1. Create a Markdown file in `_posts/` with this naming format:
`YYYY-MM-DD-your-title.md`
2. Add front matter:

```yaml
---
layout: post
title: "Your Post Title"
tags: [tag1, tag2]
---
```

3. Write content in Markdown.
4. Commit and push to `main`. GitHub Pages will publish automatically.

## Notes

- This repo contains the blog source code, not generated static output.
- For link paths in posts, prefer root-relative paths (for example, `/images/bunny.jpg`).

## License

MIT. See [LICENSE](./LICENSE).
