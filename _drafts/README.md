# /_drafts/

Blog posts that are written but not yet published. GitHub Pages ignores
directories starting with `_` by default (Jekyll convention), so files
here are NOT served from tonysoftware.com.

## Why drafts exist (Tony msg 1548, 2026-05-25)

Three blog posts shipped in 2 hours read like AI content farming, not
real indie-dev writing. Pulled 2 of 3 back here. Re-publish staggered:

- `building-skyline-on-device-boarding-pass-scanner.html` — target
  publish ~2026-06-01 (1 week stagger from Aside post).
- `building-pulse-byok-paddle-dashboard.html` — target publish
  ~2026-06-08 (2 week stagger from Aside post).

## Re-publish recipe

1. Move file from `_drafts/` to `blog/`
2. Update `datePublished` + `dateModified` in JSON-LD + article meta to the new date
3. Update `<div class="date">` in body to new date
4. Add entry to `blog/index.html` post-list
5. Add URL to `sitemap.xml`
6. POST URL to IndexNow (key at `~/.config/indexnow/tonysoftware.com.key`)
7. Commit + push

## Cadence rule (codified)

One technical blog post per week MAX on a single domain. More than
that on a single day signals "AI content farming" to both human
readers and search engines.
