# Above and Beyond Data — site

Marketing site for [abovebeyonddata.com](https://abovebeyonddata.com), built with Jekyll.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Site builds to `_site/` and serves at `http://localhost:4000`.

## Structure

- `_layouts/default.html` — site nav, footer, scripts
- `_layouts/page.html` — wraps content pages with a header band
- `assets/css/main.scss` — all styles, controlled by a type-scale system at the top
- `index.html`, `about.html`, `services.html`, `contact.html`, `services/mdm-readiness/index.html` — the five live pages

## Deployment

Pushed to `main` and served via GitHub Pages with the custom `CNAME` domain.
