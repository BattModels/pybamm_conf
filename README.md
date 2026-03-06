# PyBaMM Conference Site (Jekyll)

This project is now structured as a standard, content-first Jekyll site.

## Structure

- `_layouts/default.html`: shared page shell
- `_includes/`: reusable header/footer/head components
- `_data/*.yml`: reusable content/config data
- `*.md`: editable page content (main text)
- `assets/css/site.css`: all styling

## Content editing

Edit the main page text directly in:

- `index.md`
- `about.md`
- `speakers.md`
- `abstracts.md`
- `venue.md`
- `registration.md`
- `training.md`

Reusable lists are in:

- `_data/speakers.yml`
- `_data/institutions.yml`
- `_data/site.yml`

## Ruby version

Uses `rbenv` Ruby `3.2.4` (`.ruby-version`).

## Local run

```bash
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```
