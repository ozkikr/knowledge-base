---
url: https://electric-sql.com/product/pglite
type: article
tags: [postgres, wasm, embedded-database, typescript, browser]
date_saved: 2026-02-14
---
# PGlite - Embeddable Postgres

## Summary
PGlite is a lightweight WASM build of Postgres packaged as a TypeScript library for browser, Node.js, Bun, and Deno. Under 3MB gzipped, it runs Postgres directly in JavaScript without a Linux VM, supporting persistence via filesystem or IndexedDB.

## Key Points
- Postgres compiled to WASM in single-user mode, no VM required
- Supports in-memory, filesystem (Node/Bun), and IndexedDB (browser) persistence
- Extensible with dynamic extensions including pgvector
- Built-in reactivity with live queries and sync primitives
- Can sync with cloud Postgres via ElectricSQL's Shape protocol

## Related
- [[wasm]], [[embedded-databases]], [[local-first]], [[electicsql]]
