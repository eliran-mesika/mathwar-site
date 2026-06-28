# MathWar Public Site

Static public site for `mathwar.mesikalabs.com`.

GitHub Pages can publish this folder by selecting the repository `docs/` directory as the Pages source, or an Actions workflow can copy this folder to a Pages artifact.

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
cd /Users/eliranmesika/Documents/MathWar/docs
python3 -m http.server 8090 --bind 127.0.0.1
```

Then check `/`, `/support/`, `/privacy/`, `/terms/`, `/blog/`, `/blog/feed.json`, `/robots.txt`, and `/sitemap.xml`.
