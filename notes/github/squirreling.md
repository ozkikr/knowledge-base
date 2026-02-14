---
url: https://github.com/hyparam/squirreling
type: github-repo
languages: [JavaScript, TypeScript]
tags: [sql, streaming, async, browser, query-engine]
date_saved: 2026-02-14
---
# Squirreling

## Summary
Squirreling is a streaming async SQL engine in pure JavaScript, built for the browser. It features cell-level lazy evaluation using AsyncGenerators and async thunks, making it ideal for querying data from network sources, APIs, or LLMs where latency and cost matter.

## Key Points
- Full SQL support (read-only) with streaming input and output
- Cell-level lazy evaluation: expensive operations only execute for cells in query results
- Async user-defined functions can call APIs or LLMs
- Tiny footprint: 13kb bundle, zero dependencies, instant startup
- Unlike WASM databases, fully async with true streaming during network fetches

## Related
- [[sql]]
- [[streaming]]
- [[browser-databases]]
