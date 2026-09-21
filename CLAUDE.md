# CLAUDE.md

Personal site: Hugo + PaperMod, deployed to GitHub Pages from `master` via `.github/workflows/pages.yml`.

## Conventions

- Content is markdown under `content/`; posts go in `content/posts/`.
- Every post needs front matter with `title`, `date`, `draft`, and `tags`. Copy the shape from an existing post rather than inventing fields.
- Site-wide changes (menu, social icons, profile text, params) belong in `hugo.yaml` — not in theme files.
- Never edit anything under `themes/PaperMod/`; it is a git submodule. Override a template by copying it to `layouts/` at the repo root with the same relative path.
- `public/` and `resources/` are build output and gitignored. Don't commit them.

## Verify before declaring done

```bash
hugo --minify
```

The build must succeed. For a visual check: `hugo server -D` and open http://localhost:1313.

## Deploy

Merging or pushing to `master` deploys. There is no manual publish step.
