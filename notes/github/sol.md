---
url: https://github.com/thetinygoat/sol
type: github-repo
languages: [Rust]
tags: [web-to-markdown, cli, scraping]
date_saved: 2026-02-15
---
# SOL
## Summary
SOL is a CLI that converts web pages into clean Markdown using a headless Chromium renderer. It is designed to extract readable content even from JavaScript-heavy pages that basic scrapers often miss. The resulting output is suitable for offline reading, archiving, and LLM context preparation.

## Key Points
- Renders pages in headless Chromium before extraction for better SPA support.
- Uses readability-style content extraction to remove navigation and noise.
- Outputs Markdown directly to stdout or file with configurable render wait times.
- Includes optional user-agent customization and one-time browser setup.
- Targets practical content capture rather than full browser automation.

## Related
- [[Web Scraping]]
- [[Markdown Conversion]]
- [[LLM Context Prep]]
