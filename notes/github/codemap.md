---
url: https://github.com/JordanCoin/codemap
type: github-repo
languages: [Go]
tags: [developer-tools, llm, code-context, cli]
date_saved: 2026-02-14
---
# Codemap

## Summary
Codemap is a CLI tool that generates a "project brain" for AI — giving LLMs instant architectural context about a codebase without burning tokens. It supports tree views, diff mode, dependency flow analysis, and even a skyline visualization.

## Key Points
- Generates project tree maps with filtering by extension, depth, and exclusion patterns
- Diff mode shows changed files vs a branch (e.g., main) with line counts
- Dependency flow mode (`--deps`) maps import relationships
- Works on remote GitHub repos directly via URL
- Available via Homebrew (macOS/Linux) and Scoop (Windows)

## Related
- [[sgrep]] - semantic code search
- [[chonkie]] - text chunking for RAG
