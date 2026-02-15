---
url: https://github.com/sibyllinesoft/valknut
type: github-repo
languages: [Rust, JavaScript, HTML, CSS]
tags: [code-quality, static-analysis, cli]
date_saved: 2026-02-15
---
# Valknut
## Summary
Valknut is a Rust-native code intelligence and quality analysis CLI for large repositories. It combines structural and complexity analysis, documentation auditing, and optional AI-assisted refactoring guidance. The tool is designed for CI usage with multiple report formats and quality gates.

## Key Points
- Runs a multi-layer analysis pipeline including structure, complexity, dependency, and clone detection signals.
- Supports CI/CD workflows with machine-readable and human-friendly outputs (JSONL, HTML, Markdown, and more).
- Includes a `doc-audit` workflow for README freshness, TODO hotspots, and documentation quality checks.
- Exposes MCP capabilities via `mcp-stdio` for IDE and agent integrations.
- Offers optional Gemini-based refactoring oracle mode for guided recommendations.

## Related
- [[Static Analysis]]
- [[Code Quality Gates]]
- [[Model Context Protocol]]
