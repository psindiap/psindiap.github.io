# Partha Sarathi Purkayastha — academic website

Personal website at https://psindiap.github.io, built with Jekyll and the MIT-licensed [al-folio](https://github.com/alshedivat/al-folio) theme.

## Editing content

- `_pages/about.md`: homepage biography.
- `_data/profile.json`: education, experience, teaching, projects, awards, community activities, and skills. Shared by the individual pages and full online CV.
- `_data/publications.json`: publication titles, authors, venue/status, summaries, links, and homepage selection.
- `_data/updates.json`: dated homepage news.
- `_bibliography/papers.bib`: bibliography for reuse. Keep synchronized with publication metadata.
- `assets/pdf/PARTHA_SARATHI_PURKAYASTHA_CV.pdf`: downloadable CV, currently October 2026.
- `_sass/_academic.scss`: profile layout and responsive styling.

The October 2026 CV takes precedence over the older CV where dates and metrics differ. Earlier experience, teaching, projects, and awards are retained on the detailed pages. Publication links were checked against publisher, workshop, and arXiv records. Unpublished work from private planning notes is not included.

## Preview

Use Ruby 3.2 or newer and ImageMagick:

```sh
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --host 127.0.0.1
```

For the production build:

```sh
JEKYLL_ENV=production bundle exec jekyll build
```

Pushes to `master` run the existing deployment workflow, which builds the site and publishes to `gh-pages`. GitHub Pages serves that branch. The `psethzp` account has collaborator/push access; the repository remains owned by `psindiap`.
