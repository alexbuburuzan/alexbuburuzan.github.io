# alexbubu.com

Personal site of Alexandru Buburuzan. Built with [Hugo](https://gohugo.io/) and
the [Wowchemy](https://wowchemy.com) academic theme, deployed to GitHub Pages by
`.github/workflows/hugo.yaml` on every push to `main`.

## Running locally

Requires **Hugo extended 0.98.0** (the version the deploy workflow pins) and a
**Go** toolchain — the theme is consumed as a Hugo Module, so Hugo shells out to
`go` to fetch it on first build.

```sh
brew install hugo go   # or download hugo_extended 0.98.0 from the Hugo releases page
hugo server            # http://localhost:1313
```

Newer Hugo releases are not backward compatible with Wowchemy v5; pin 0.98.0 to
match CI.

## Layout

| Path | Purpose |
| --- | --- |
| `config/_default/` | Site config, params, languages. `menus.yaml` is intentionally empty — the site runs without a navbar. |
| `content/authors/admin/` | The bio, profile links, and education shown on the homepage. |
| `content/home/` | Homepage sections (about, publications, experience). |
| `content/publication/` | One page bundle per paper: `index.md`, `cite.bib`, `featured.png`. |
| `content/photography.md` | Gallery contents and running order. |
| `content/mobi.html`, `content/anydoormed.html` | Standalone paper sites. Deliberately plain HTML with no Hugo templating so they stay portable; served at `/mobi` and `/anydoormed` with assets from `static/mobi/` and `static/anydoormed/`. |
| `layouts/` | Theme overrides. `partials/views/pub_item.html` is the single renderer for publication listings. |
| `assets/scss/custom.scss` | All site styling — design tokens plus overrides, numbered by section. |
| `assets/media/photos/` | Photography originals. Never served directly; `layouts/photography/gallery.html` generates responsive WebP derivatives. |

## Adding things

**A publication** — create `content/publication/<key>/` with `index.md`,
`cite.bib`, and a `featured.png`. Keep `featured.png` under ~1600px wide: the
theme uses it directly as the page's `og:image`, so it is published as-is.

**A photograph** — drop the file in `assets/media/photos/` and add a `- file:`
line to `content/photography.md` at the position you want it in the running
order. The build fails loudly if a listed file is missing.
