---
url: https://github.com/kiki-ki/go-qo
type: github-repo
languages: [Go]
tags: [tui, sql, json, csv, cli, data-processing]
date_saved: 2026-02-14
---
# qo - Interactive TUI for Querying JSON/CSV with SQL

## Summary
qo is a minimalist TUI tool that lets you query JSON, CSV, and TSV files using SQL syntax. It's pipeline-native (reads stdin, writes stdout) and interactive — you can explore data in a TUI, refine your query, then pipe results to other tools.

## Key Points
- Query JSON/CSV/TSV with familiar SQL syntax
- Pipe-friendly TUI: works seamlessly in Unix pipelines (e.g., `curl | qo | jq`)
- Interactive mode lets you see results before committing
- Supports JOINs across multiple files
- Format conversion between JSON, CSV, and TSV

## Related
- [[jq]] - JSON processor
- [[making-macos-bearable]] - Terminal-focused workflow
