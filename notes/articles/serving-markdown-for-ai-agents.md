---
url: https://code.dblock.org/2026/01/15/serving-markdown-for-ai-agents.html
type: article
tags: [ai-agents, markdown, web, jekyll, content-serving, third-audience]
date_saved: 2026-02-14
---
# Serving Markdown for AI Agents in Jekyll

## Summary
Inspired by Dries Buytaert's "The Third Audience" concept (humans, search engines, AI agents), this post describes serving source markdown files alongside HTML for AI agent consumption. Each blog post gets a `.md` alternate URL discoverable via `<link rel="alternate" type="text/markdown">`.

## Key Points
- AI agents are the "third audience" for websites, preferring clean structured content over HTML
- Implementation uses GitHub Actions to copy markdown source files to `_site` during Jekyll build
- Discoverable via `<link rel="alternate" type="text/markdown">` in HTML head
- No custom Jekyll plugins needed — works with GitHub Pages
- Entire feature was implemented by Claude AI

## Related
- [[ai-agents]]
- [[web-standards]]
- [[content-for-llms]]
- [[jekyll]]
