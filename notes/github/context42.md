---
url: https://github.com/zenbase-ai/context42
type: github-repo
tags: [code-style, ai-analysis, gemini, developer-tools]
date_saved: 2026-02-14
---

# Context42

## Summary
A tool that discovers your team's implicit code style by analyzing your codebase with Google Gemini. It recursively scans files, groups by language, and generates per-language style guides (e.g., ts.md, py.md) based on actual patterns.

## Key Points
- Uses Gemini CLI concurrently to analyze code patterns
- Respects .gitignore, groups files by language extension
- Generates style guides per language based on actual codebase conventions
- SQLite cache for incremental runs; configurable concurrency
- Makes implicit coding conventions explicit for team alignment

## Related
- [[code-style]] [[linting]] [[gemini]] [[cursor-rules]]
