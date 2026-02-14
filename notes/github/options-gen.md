---
url: https://github.com/kazhuravlev/options-gen
type: github-repo
languages: [Go]
tags: [code-generation, functional-options, golang, boilerplate]
date_saved: 2026-02-14
---
# options-gen - Codegen for Functional Options in Go

## Summary
options-gen is a Go code generator that eliminates boilerplate when implementing the functional options pattern. It generates type-safe constructors, `WithX()` setter functions, and validation logic from struct definitions with tags.

## Key Points
- Generates functional options pattern code from annotated structs via `go generate`
- Supports mandatory parameters, defaults (tags, variables, or functions), and validation
- Produces type-safe `WithX()` setter functions for optional fields
- Supports Go generics
- Uses struct tags like `option:"mandatory"` and `default:"3"`

## Related
- [[golang]]
- [[code-generation]]
- [[design-patterns]]
