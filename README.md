# lguanrui.github.io

Personal homepage of Guanrui Li, built with [Hugo](https://gohugo.io/) and the
[HugoBlox](https://hugoblox.com/) research-group theme, sharing the custom layouts and
design of the [ACP Lab website](https://github.com/acp-lab/acplab-web).

## How to update

- **A paper**: add a folder under `content/journal/`, `content/conference/` or
  `content/preprint/` with `index.md`, `cite.bib` and a `featured.png` teaser. Copy an
  existing folder and edit the front matter.
- **A news item**: add `content/post/<year>-<slug>/index.md` (plus `featured.jpg`).
- **Bio, links, education**: `content/authors/admin/_index.md`.
- **Home page sections**: `content/_index.md`. **Teaching**: `content/teaching/index.md`.
- **CV**: replace `static/uploads/cv_guanrui.pdf`.
- **Menu**: `config/_default/menus.yaml`. **Colors and fonts**: `config/_default/params.yaml`
  (`appearance`), `data/themes/`, `data/fonts/`.

## Build locally

Needs Hugo extended 0.135.0 and Go (for the theme modules).

```bash
hugo server --disableFastRender   # http://localhost:1313/
```

## Deploy

Pushes to `master` run `.github/workflows/publish.yaml`, which builds the site and deploys
it to GitHub Pages. The repository's Pages source must be set to **GitHub Actions**.
