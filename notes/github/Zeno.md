---
url: https://github.com/internetarchive/Zeno
type: github-repo
languages: [Go]
tags: [web-crawler, warc, archiving, internet-archive]
date_saved: 2026-02-14
---
# Zeno - State-of-the-art Web Crawler

## Summary
Zeno is a high-performance web crawler by the Internet Archive, designed for wide crawls or single-page archiving. It records traffic into WARC files using the gowarc module and emphasizes portability, performance, and simplicity. Named after Zenodotus, the first librarian of the Library of Alexandria.

## Key Points
- Records web traffic into WARC format files
- Supports both wide crawls and single-page archiving
- Requires Go 1.25+; optional CGO for faster URL parsing
- Uses WHATWG URL parser via ada-url/goada
- Maintained by the Internet Archive

## Related
- [[crawley]] - another Go web crawler
- [[web-archiving]]
- [[WARC]]
