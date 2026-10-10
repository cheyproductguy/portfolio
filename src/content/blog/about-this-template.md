---
draft: true
title: "About This Template"
description: "A README-style post that explains how to use and customize the blog template."
date: "2025-02-26"
tags:
  - Docs
  - Template
series: Building-Redoed
---
draft: true
# About This Template

This post acts like a **README** for the template. It explains the basics of how the template works and where you can make changes.

---
draft: true
## Folder Structure

A typical Astro content setup might look like this:

```txt
src/
  components/     # UI components
  layouts/        # Page layouts
  pages/          # Route-based pages
  content/
    blog/         # Markdown/MDX blog posts
    projects/     # Markdown/MDX projects
```

---
draft: true
## Writing Posts

Posts live in the `src/content/blog/` folder.
Each post needs **frontmatter** at the top, like this:

```yaml
---
draft: true
title: "My Post"
description: "A short summary."
date: "2025-02-20"
tags:
  - Example
  - Demo
---
draft: true
```

## Adding Projects

Projects live in the `src/content/projects/` folder.
Each project needs **frontmatter** at the top, like this:

```yaml
---
draft: true
title: "FormSync"
description: "Serverless forms with instant email notifications, reCAPTCHA, and zero backend. Just drop in a <form>."
liveUrl: https://example.com
githubUrl: https://github.com
image: { url: "/formsync.jpeg", alt: "FormSync thumbnail" }
---
draft: true
```

## Styling Notes

- Images should be placed in `public/` or loaded from a URL.
- Markdown supports **headings, lists, blockquotes, tables, and code** — see the [Markdown Style Guide](/blog/markdown-style-guide).
- Default placeholder images will show if no thumbnail is provided.

---
draft: true
## Development

To run the project locally:

```bash
pnpm install
pnpm run dev
```

Then visit `http://localhost:4321` to preview the site.

---
draft: true
## Customization

You can edit:

- **Colors and fonts** → via `global.css`
- **Layout** → in `src/layouts/`
- **Components** → in `src/components/`

---
draft: true
## Closing

This template is meant to be a clean starting point for a portfolio.
Feel free to **remove this post** once you’re ready to publish real content.

