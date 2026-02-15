---
url: https://github.com/JaredStewart/coderlm
type: github-repo
languages: [Rust, Python, Shell]
tags: [code-indexing, tree-sitter, llm-agents, recursive-language-model]
date_saved: 2026-02-15
---
# coderlm
## Summary
coderlm is a tree-sitter-powered code indexing server that gives LLM agents precise, on-demand code context. It follows a Recursive Language Model pattern so agents query structure and symbols instead of loading entire repositories.
## Key Points
- Indexes repositories into searchable symbols, references, and source ranges.
- Exposes a JSON API for targeted retrieval (callers, tests, grep, implementations).
- Reduces context-window pressure by replacing broad file reads with precise lookups.
- Includes workflow support for Claude Code integration.
## Related
- [[Code Indexing]]
- [[Tree-sitter]]
- [[LLM Context Retrieval]]
