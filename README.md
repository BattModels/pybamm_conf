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

## Google Analytics

This site supports Google Analytics 4 via a configurable tag in `_includes/head.html`.

To enable it:

1. Create a GA4 property and a web data stream in Google Analytics.
2. Copy the Google tag / measurement ID (typically starts with `G-`).
3. Set `google_analytics_id` in `_config.yml`.
4. Rebuild and deploy the site.

If `google_analytics_id` is blank, the analytics script is not included.
