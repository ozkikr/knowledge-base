---
url: https://github.com/cloudflare/workerd
type: github-repo
languages: [C++, JavaScript]
tags: [cloudflare, runtime, javascript, wasm, edge-computing, workers]
date_saved: 2026-02-14
---
# workerd

## Summary
workerd is the open-source JavaScript/Wasm server runtime that powers Cloudflare Workers. It can be used as an application server for self-hosting Workers apps, as a local development tool, or as a programmable HTTP proxy.

## Key Points
- Server-first design with web-standard APIs (fetch, etc.)
- Nanoservices architecture: decoupled components with local function call performance
- Capability bindings instead of global namespaces — immune to SSRF attacks
- Always backwards compatible: version number is a date, old compatibility dates always work
- Homogeneous deployment: all nanoservices on every machine for easy load balancing

## Related
- [[cloudflare-workers]]
- [[edge-computing]]
- [[v8]]
- [[wasm]]
