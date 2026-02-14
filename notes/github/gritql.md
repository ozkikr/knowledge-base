---
url: https://github.com/honeycombio/gritql
type: github-repo
tags: [code-search, code-rewriting, query-language, rust, linting]
date_saved: 2026-02-14
---

# GritQL

## Summary
A declarative query language for searching, linting, and modifying source code. Any code snippet is a valid query, making it easy to start without learning AST details. Built in Rust for performance, scaling to 10M+ line repos. Now maintained under biomejs/gritql.

## Key Points
- Any code snippet is a valid GritQL query — no AST knowledge needed
- Supports 12+ target languages: JS/TS, Python, JSON, Java, Go, Rust, SQL, etc.
- Built-in module system with 200+ reusable standard patterns
- Auto-fix rules for fast remediation; usable as custom lints via `grit check`
- Rust-powered, scales to very large codebases

## Related
- [[code-search]] [[ast]] [[linting]] [[codemods]] [[biome]]
