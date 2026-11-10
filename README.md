# romerocruzsa.github.io

Personal academic site built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
Jekyll template (a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)).

## Editing content

* `_config.yml` - site title, sidebar bio, and profile links (`author:` block)
* `_pages/about.md` - home page ("About")
* `_data/news.yml` - news items shown on the home page (Markdown allowed in `body`)
* `_publications/` - one Markdown file per paper; PDFs live in `papers/`, BibTeX in `files/`
* `_portfolio/` - Software & Code entries
* `_pages/cv.md` - CV, including honors & awards
* `_data/navigation.yml` - top menu

## Deploying

`.github/workflows/jekyll.yml` builds and deploys the site on every push to `gh-pages`.
In the repository settings, Pages must be set to **Source: GitHub Actions**.

## Local preview

```
bundle install
npm run build:js   # only after editing assets/js
bundle exec jekyll serve -l -H localhost
```
