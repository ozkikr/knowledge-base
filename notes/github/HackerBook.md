---
url: https://github.com/DOSAYGO-STUDIO/HackerBook
type: github-repo
languages: [JavaScript, HTML, Shell]
tags: [hacker-news, archive, sqlite-wasm, static-site, etl]
date_saved: 2026-02-15
---
# HackerBook
## Summary
HackerBook is a static, offline-friendly archive of Hacker News that can run entirely in the browser. It relies on SQLite compiled to WebAssembly plus sharded data files to keep client-side querying fast and portable. The repo includes both a ready-to-browse archive and build pipeline scripts.

## Key Points
- Delivers browser-side querying with SQLite WASM over sharded, compressed datasets.
- Designed for immutable static hosting with hash-based shard filenames.
- Includes ETL and indexing workflows for rebuilding or updating the archive.
- Emphasizes offline access, reproducibility, and long-term archival durability.

## Related
- [[SQLite WASM]]
- [[Data Archiving]]
- [[Static Sites]]
- [[ETL]]
