# Junteng Liu — Personal Homepage

Personal academic homepage of **Junteng Liu**, first-year Ph.D. candidate at the HKUST NLP Group.

- Homepage (About): [`_pages/about.md`](_pages/about.md) — personal details, research interests, education, research experience, publications, awards, and contact information.
- Publications: [`_publications/`](_publications/) rendered on the [Publications page](_pages/publications.html).

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

## Deployment

The site is configured as a project page (`url: https://trenchdragonflystrut.github.io`, `baseurl: /LJT-Homepage` in `_config.yml`). The `Build and Deploy Jekyll` workflow builds the site on every push to `master` and uploads the built site as a workflow artifact.

To publish it on GitHub Pages:

1. In the repository **Settings → Pages**, set **Source** to **GitHub Actions**.
2. In the **Actions** tab, run the **Build and Deploy Jekyll** workflow manually with the **deploy** option checked.
