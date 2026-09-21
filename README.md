# ArnobKumarSaha.github.io

Personal site — built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme, deployed to GitHub Pages.

Live at <https://arnobkumarsaha.github.io/>

## Layout

```
content/          posts and pages (markdown)
  about.md        the About page
  posts/          blog posts
archetypes/       front-matter template for `hugo new`
themes/PaperMod/  theme (git submodule)
hugo.yaml         site config: title, menu, profile, social links
.github/workflows/pages.yml   build + deploy on push to master
```

## Prerequisites

- Hugo **extended** ≥ 0.128.2 (`brew install hugo`)
- The theme submodule:

```bash
git submodule update --init --recursive
```

## Run locally

```bash
hugo server -D          # http://localhost:1313, -D includes drafts
```

Live reload is on; edit a file under `content/` and the browser refreshes.

## Write a post

```bash
hugo new content/posts/my-post.md
```

Set `draft: false` in the front matter when it's ready — drafts are excluded from the production build.

## Build

```bash
hugo --minify           # output lands in ./public (gitignored)
```

## Deploy

Push to `master`. The workflow in `.github/workflows/pages.yml` builds the site and publishes it via GitHub Pages.

One-time setup in the repo: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
