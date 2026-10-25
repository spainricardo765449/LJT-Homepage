# LJT-Homepage

Personal academic homepage of **Junteng Liu**, a PhD candidate at the HKUST NLP Group.

The site is built with [Jekyll](https://jekyllrb.com) using the
[Academic Pages](https://github.com/academicpages/academicpages.github.io) template,
which is itself a fork of the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) theme.

## Site content

- `_pages/about.md` — homepage with the biography, research interests, education,
  research experience, publications, honors and contact information
- `_publications/` — one Markdown file per paper, rendered on the `/publications/` page
- `_config.yml` — site-wide settings (title, author profile, social links)
- `_data/navigation.yml` — links shown in the site header

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>.

## Publishing

The site is built and deployed by GitHub Actions (`.github/workflows/jekyll.yml`).
To publish it, enable GitHub Pages for this repository under
**Settings → Pages → Build and deployment → Source: GitHub Actions**.
