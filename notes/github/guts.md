---
url: https://github.com/coder/guts
type: github-repo
languages: [Go, TypeScript]
tags: [code-generation, golang, typescript, type-conversion, frontend-backend-sync]
date_saved: 2026-02-14
---
# Guts (Go Unto TypeScript)

## Summary
A Go library that converts Golang types to TypeScript definitions, enabling consistent type definitions across frontend and backend. Used in production by Coder to keep their API types in sync.

## Key Points
- Converts Go structs, generics, and types to TypeScript interfaces
- Library-based (not CLI) for code-level configuration
- Uses goja (JS runtime in Go) with TypeScript compiler API for serialization
- Supports generics, comments preservation, and custom mutations
- Used in Coder's production codebase

## Related
- [[envbuilder]] - another Coder project
