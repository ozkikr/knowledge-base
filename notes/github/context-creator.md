---
url: https://github.com/matiasvillaverde/context-creator
type: github-repo
tags: [rust, context-engineering, ai, tree-sitter, mcp]
date_saved: 2026-02-14
---

# Context Creator

## Summary
A high-performance Rust CLI for optimizing context engineering in agentic programming. Uses tree-sitter to build dependency graphs of codebases, selecting only relevant files for AI context windows instead of naively concatenating everything.

## Key Points
- Dependency-aware context building using tree-sitter AST parsing
- Supports Python, TypeScript, JavaScript, and Rust
- MCP server integration for AI assistants to query codebases programmatically
- Dramatically reduces token usage vs naive file concatenation (e.g., 50K relevant tokens vs 500K noise)
- Like repomix but faster and smarter

## Related
- [[tree-sitter]] - parsing library used for AST analysis
- [[mcp]] - Model Context Protocol integration
- [[repomix]] - similar tool for context preparation
