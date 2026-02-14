---
url: https://github.com/pamburus/hl
type: github-repo
languages: [Rust]
tags: [logging, cli, json-logs, logfmt, log-viewer]
date_saved: 2026-02-14
---
# hl — Fast Log Viewer and Processor

## Summary
hl is a high-performance log viewer and processor that converts JSON and logfmt logs into human-readable format. Built in Rust for efficiency, it can scan logs at ~2 GiB/s and reindex at ~10 GiB/s, handling hundreds of gigabytes across local files.

## Key Points
- Automatic pager integration (defaults to `less`)
- Field-based filtering, level filtering, and timestamp range filtering with intuitive formats
- High-speed chronological sorting with automatic indexing
- Live follow mode for streaming logs
- Field visibility control and multi-line expansion options

## Related
- [[logfmt]]
- [[structured-logging]]
- [[cli-tools]]
