# drum.zone

Personal blog built with Jekyll. Existing posts and the Hitchens-based theme live in this repository.

## Local development

Install the Ruby version in `.ruby-version` (for example, `rbenv install -s`), then:

```sh
bundle install
bundle exec jekyll serve
```

Production build:

```sh
JEKYLL_ENV=production bundle exec jekyll build --trace
```

## Deployment

GitHub Actions builds pull requests and deploys successful builds on `master` to GitHub Pages. Repository Settings → Pages must use **GitHub Actions** as the source. Deployment uses the built-in `GITHUB_TOKEN`; no personal access token is required. The custom domain is `drum.zone`.

## OpenClaw Calendar

OAuth information pages are `openclaw.md`, `openclaw-privacy.md`, and `openclaw-terms.md`:

- https://drum.zone/openclaw/
- https://drum.zone/openclaw/privacy/
- https://drum.zone/openclaw/terms/

Keep their disclosures aligned with the integration’s actual data handling. Never commit OAuth credentials, tokens, or private calendar data here.
