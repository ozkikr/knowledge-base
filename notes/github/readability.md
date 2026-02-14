---
url: https://github.com/mozilla/readability
type: github-repo
languages: [JavaScript]
tags: [parsing, reader-view, content-extraction, mozilla]
date_saved: 2026-02-14
---
# Mozilla Readability.js

## Summary
Readability.js is a standalone version of the readability library used in Firefox Reader View. It extracts the main readable content from web pages by parsing DOM documents, stripping clutter, and returning clean article content with metadata.

## Key Points
- Standalone extraction of Firefox Reader View's content parsing logic
- Configurable options: debug mode, max elements, character thresholds, class preservation
- Supports JSON-LD metadata extraction from Schema.org markup
- Works in browsers and Node.js (with external DOM library like jsdom)
- Available on npm as `@mozilla/readability`

## Related
- [[web-scraping]] [[content-extraction]] [[firefox]] [[dom-parsing]]
