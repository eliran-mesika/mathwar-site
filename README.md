# MathWar Public Site

Static public site for `mathwar.mesikalabs.com`.

GitHub Pages publishes this repository from the `main` branch root.

The canonical local checkout for this public site is:

```sh
/Users/eliranmesika/Repos/mathwar-site
```

Do not update `/Users/eliranmesika/Documents/MathWar/docs` or `/Users/eliranmesika/Repos/MathWar/docs` for public-site changes unless the site ownership is deliberately changed first.

## Files

- `index.html`
- `support/index.html`
- `privacy/index.html`
- `terms/index.html`
- `blog/index.html`
- `blog/feed.json`
- `version.json`
- `robots.txt`
- `sitemap.xml`
- `assets/`

## Validation

```sh
cd /Users/eliranmesika/Repos/mathwar-site
python3 -m http.server 8090 --bind 127.0.0.1
```

Then check `/`, `/support/`, `/privacy/`, `/terms/`, `/blog/`, `/blog/feed.json`, `/robots.txt`, and `/sitemap.xml`.

## Hosted Status

DNS currently points `mathwar.mesikalabs.com` at GitHub Pages. HTTPS must be fixed in GitHub Pages before App Store review uses this domain as a production support/privacy/terms target.
