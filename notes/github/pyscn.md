---
url: https://github.com/ludo-technologies/pyscn
type: github-repo
languages: [Go, Python]
tags: [code-quality, static-analysis, dead-code, clone-detection, mcp]
date_saved: 2026-02-14
---
# pyscn

## Summary
pyscn is an intelligent Python code quality analyzer built with Go and tree-sitter, designed for "vibe coders" using AI coding assistants. It performs structural analysis including dead code detection, clone detection, coupling metrics, and cyclomatic complexity at 100,000+ lines/sec. Includes MCP integration for use with Claude Code, Cursor, and other AI tools.

## Key Points
- CFG-based dead code detection for unreachable code paths
- Multi-algorithm clone detection (Type 1-4) with LSH acceleration
- Coupling metrics (CBO) for tracking architecture quality
- Built with Go + tree-sitter for high performance (100k+ lines/sec)
- MCP integration for seamless use with AI coding assistants

## Related
- [[static-analysis]]
- [[code-quality]]
- [[MCP]]
- [[AI-coding-assistants]]
