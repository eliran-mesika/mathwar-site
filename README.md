# BrainMarshal Public Site

Static public site for BrainMarshal. The canonical domain is `brainmarshal.mesikalabs.com`, including support/privacy/terms links. GitHub Pages publishes the main branch root. Cloudflare redirects the legacy `mathwar.mesikalabs.com` hostname to the canonical domain while preserving paths and query strings.

This repository owns the website. Do not edit the legacy `MathWar/docs` website copy. Local checkout: `/Users/eliranmesika/Projects/MesikaLabs/mathwar-site`.

## Validation

Run `python3 -m http.server 8090 --bind 127.0.0.1` and check `/`, `/support/`, `/privacy/`, `/terms/`, `/blog/`, `/blog/feed.json`, `/version.json`, `/robots.txt`, and `/sitemap.xml` at phone and desktop widths.

## Release status

BrainMarshal 1.0 (1), bundle `com.mesikalabs.brainmarshal`, Apple ID `6809766309`. Device QA is underway. No public release or new TestFlight distribution is claimed. The new hero selection capture is current; gameplay gallery and older blog artwork are explicitly historical development images. Current HTTPS support/privacy routes returned HTTP 200 on 2026-09-08.
