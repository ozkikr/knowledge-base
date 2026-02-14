---
url: https://github.com/takashiishida/arxiv-to-prompt
type: github-repo
tags: [arxiv, latex, llm, research-tools, cli]
date_saved: 2026-02-14
---
# arxiv-to-prompt

## Summary
A CLI tool that transforms arXiv papers into a single flattened LaTeX source suitable for use as an LLM prompt. Downloads source files, resolves \input/\include commands, and optionally strips comments and appendices to shorten prompts.

## Key Points
- Accepts arXiv IDs or full URLs; auto-downloads latest version with local caching
- Options to remove comments (`--no-comments`), appendices (`--no-appendix`), and extract specific sections
- Python API available for programmatic use (`process_latex_source()`)
- Integrates with Simon Willison's `llm` CLI: `arxiv-to-prompt 1706.03762 | llm -s "explain this paper"`
- Companion MCP server (arxiv-latex-mcp) available for agent integration

## Related
- [[arxiv]]
- [[research-tools]]
- [[llm-prompting]]
