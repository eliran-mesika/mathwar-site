# BrainMarshal Public Site

Static public site for BrainMarshal. The canonical domain is `brainmarshal.mesikalabs.com`, including support/privacy/terms links. GitHub Pages publishes the main branch root. Cloudflare redirects the legacy `mathwar.mesikalabs.com` hostname to the canonical domain while preserving paths and query strings.

This repository owns the website. Do not edit the legacy `MathWar/docs` website copy. Local checkout: `/Users/eliranmesika/Projects/MesikaLabs/mathwar-site`.

## Validation

Run `python3 -m http.server 8090 --bind 127.0.0.1` and check `/`, `/support/`, `/privacy/`, `/terms/`, `/blog/`, `/blog/feed.json`, `/version.json`, `/robots.txt`, and `/sitemap.xml` at phone and desktop widths.

## Release status

BrainMarshal 1.0 (2), bundle `com.mesikalabs.brainmarshal`, Apple ID `6809766309`, was resubmitted on 2026-09-15 at 17:55 local with six clean screenshots per device. App Store Connect confirmed Waiting for Review, submission `d8d67618-c546-48b6-90bb-648a5faf8dca`. This is not approval or public availability.

The homepage shows current training selection, campaign map, hero selection, question, boss and gate screenshots. Full original iPhone PNGs are preserved in `assets/screenshots/2026-09-15/source/`; the page serves 600px WebP derivatives. Historic blog imagery remains historical.
