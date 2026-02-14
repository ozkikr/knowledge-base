---
url: https://github.com/JohannesKaufmann/html-to-markdown
type: github-repo
tags: [golang, html, markdown, converter, web-scraping]
date_saved: 2026-02-14
---
# html-to-markdown

## Summary
A robust Go library and CLI tool that converts HTML (including entire websites) into clean, readable Markdown. Supports complex formatting like nested lists, blockquotes, code blocks, tables (with rowspan/colspan), and smart escaping. Extensible via plugins.

## Key Points
- Handles bold/italic within words, nested lists, multi-line links, and code blocks with proper backtick handling
- Smart escaping — only escapes special characters when necessary to avoid accidental rendering
- Plugin system for extensions (e.g., strikethrough, tables with alignment)
- Available as Go library, CLI tool, online demo, and REST API
- v2 rewrite with `WithDomain` for converting relative links to absolute

## Related
- [[web-scraping]]
- [[markdown]]
- [[golang]]
