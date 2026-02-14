---
url: https://github.com/plotnik-lang/plotnik
type: github-repo
languages: [Rust]
tags: [tree-sitter, query-language, type-safety, code-analysis, parsing]
date_saved: 2026-02-14
---
# Plotnik - Typed Queries for Tree-sitter

## Summary
Plotnik is a type-safe query language for Tree-sitter that makes data extraction from syntax trees declarative. Instead of writing imperative navigation code, you write patterns and get typed data back, with the query itself serving as the type definition.

## Key Points
- Static type inference from query structure
- Named expressions for composition, recursion for nested structures
- Tagged/discriminated unions support
- TypeScript type generation, WASM support, LSP and editor extensions
- Full validation against grammar rejects queries that can never match
- Supports 80+ languages via arborium grammar collection

## Related
- [[tree-sitter]], [[parsing]], [[code-analysis]], [[rust]], [[type-systems]]
