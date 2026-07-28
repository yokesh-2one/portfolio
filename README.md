# 2one — Work

A single, unified portfolio for **2one Solutions** — a design and product studio working across strategy, branding, UX, and digital transformation.

It's a self-contained static site (one `index.html`, no build step) that presents 2one's case studies with:

- A clean, on-brand monochrome UI (2one design tokens: Satoshi/Inter, neutral palette).
- **Discipline filters** (Branding, Product Design, UX, SaaS, etc.) and **live search**.
- Project cards with descriptions, outcome metrics, tags, and links to each case study.

## Run locally

Just open the file in a browser:

```bash
# macOS
open index.html
# Windows
start index.html
```

No dependencies or build step required.

## Deploy

Because it's a single static file, it can be hosted anywhere — GitHub Pages, Netlify, Vercel, or any static host. For GitHub Pages, enable Pages on the repo and serve from the root of the default branch.

## Editing content

All projects live in the `PROJECTS` array inside `index.html`. Each entry:

```js
{
  title: "Project name",
  year: "2024",
  tags: ["Product Design", "Web"],
  desc: "Short description.",
  metrics: ["40% faster onboarding"], // optional
  url: "https://…"                    // optional
}
```
