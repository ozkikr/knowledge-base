---
url: https://blog.tangled.org/docs
type: article
tags: [documentation, pandoc, static-sites, nix, web-development]
date_saved: 2026-02-15
---
# we rolled our own documentation site
## Summary
A practical write-up on building a lightweight docs site using Pandoc instead of heavier documentation frameworks. The author explains design goals (no JavaScript dependency, low complexity, easy styling) and how they customized chunked HTML output to create a maintainable docs experience. It also includes deployment details with Nix and nginx.

## Key Points
- Chose Pandoc for simplicity, easy styling, and auto-generated TOC/page chunking.
- Customized the default chunked HTML template to keep TOC visible as a sidebar.
- Implemented mobile TOC behavior using modern HTML/CSS approaches (including popover) instead of JS.
- Added pragmatic search via Google site search and a single-page export for Ctrl+F workflows.
- Uses a Nix derivation plus nginx config for reproducible build/deploy operations.

## Related
- [[pandoc]]
- [[technical-documentation]]
- [[static-site-generation]]
