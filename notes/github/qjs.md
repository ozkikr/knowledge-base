---
url: https://github.com/fastschema/qjs
type: github-repo
languages: [Go, JavaScript]
tags: [javascript-runtime, quickjs, wasm, wazero, embedding]
date_saved: 2026-02-14
---
# QJS

## Summary
QJS is a CGO-free JavaScript runtime for Go applications, built on the QuickJS engine and Wazero WebAssembly runtime. It enables safe and efficient JavaScript execution with full ES2023 support, async/await, and seamless Go-JS interoperability.

## Key Points
- CGO-free — pure Go implementation via WebAssembly (Wazero)
- Full ES2023 compatibility via QuickJS NG fork
- ProxyValue support for zero-copy sharing of Go values with JS
- Outperforms Goja and moderncQuickJS in benchmarks
- Memory-safe sandboxed execution with configurable limits

## Related
- [[QuickJS]]
- [[WebAssembly]]
- [[Wazero]]
- [[Go Embedding]]
