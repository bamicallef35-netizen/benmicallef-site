# benmicallef-site

The personal site: one page plus a sourced Roche chronology. Static HTML and one stylesheet; no framework, no build step, no cookies, no tracking.

```
index.html        identity line, thesis, works, writing, contact, colophon
roche/index.html  renders roche/roche.json — the single source of truth for every Roche claim
style.css         the same stylesheet the GitHub Pages demos use
vercel.json       clean URLs
```

Run locally with any static server, for example `python3 -m http.server 8080`.

The stylesheet is deliberately plain: IBM Plex Mono, near-monochrome, one accent, hairline rules, no cards. A copy of it lives in each demo repository so the demos and the site match exactly; change it here first.

Text and data: CC BY 4.0. Code: MIT.
