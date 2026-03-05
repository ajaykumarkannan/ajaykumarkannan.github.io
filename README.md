# ajaykumarkannan.github.io

Personal website and resume for Ajay Kannan, hosted at [ajaykannan.ca](https://ajaykannan.ca).

## Stack

- **Jekyll** — static site generator
- **GitHub Pages** — hosting via GitHub Actions CI (`jekyll-gh-pages.yml`)
- Custom HTML/CSS layout — no theme dependencies

## Structure

```
_layouts/default.html   # Page layout with header and photo
assets/
  css/style.css         # All styles
  images/ajay.jpg       # Profile photo
index.md                # Resume content
_config.yml             # Jekyll config
```

## Local development

```bash
bundle exec jekyll serve
```

Then open `http://localhost:4000`.
