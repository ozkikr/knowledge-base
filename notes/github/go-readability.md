---
url: https://github.com/go-shiori/go-readability
type: github-repo
tags: [golang, html-parsing, readability, content-extraction]
date_saved: 2026-02-14
---
# go-readability

## Summary
Go package that extracts main readable content and metadata from HTML pages, based on Mozilla's Readability.js. Removes clutter like ads, scripts, and navigation to produce clean text and HTML output. Includes a CLI tool.

## Key Points
- Line-by-line port of Mozilla Readability.js (v0.5.0 compatible)
- Extracts title, author, excerpt, site name, image, favicon
- Available as Go library (`FromURL`, `FromReader`) and CLI
- Outputs both text and HTML content
- Stable and production-ready

## Related
- [[content-extraction]]
- [[web-scraping]]
- [[Mozilla Readability]]
