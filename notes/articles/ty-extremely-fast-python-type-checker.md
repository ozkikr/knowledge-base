---
url: https://astral.sh/blog/ty
type: article
tags: [python, type-checking, rust, astral, language-server, developer-tools]
date_saved: 2026-02-14
---
# ty: An Extremely Fast Python Type Checker and Language Server

## Summary
ty is Astral's new Python type checker and language server, written in Rust. It's designed as an alternative to mypy, Pyright, and Pylance, offering 10-60x faster performance without caching and incremental updates in milliseconds for editor use.

## Key Points
- 10-60x faster than mypy and Pyright; incremental updates in ~4.7ms on PyTorch (80x faster than Pyright)
- Built from the ground up for incremental computation, powering a language server
- Features first-class intersection types, advanced type narrowing, and reachability analysis
- Rust compiler-inspired diagnostic system with multi-file context
- Available via `uv tool install ty@latest` and VS Code extension

## Related
- [[ruff]]
- [[uv]]
- [[mypy]]
- [[python-type-checking]]
