---
url: https://github.com/nao1215/filesql
type: github-repo
languages: [Go]
tags: [sql, csv, parquet, excel, sqlite, driver]
date_saved: 2026-02-14
---
# filesql — SQL Driver for CSV, TSV, Parquet, Excel

## Summary
filesql is a Go SQL driver that lets you query CSV, TSV, LTSV, Parquet, and Excel files using SQLite3 SQL syntax. It supports compressed files (gzip, bzip2, xz, zstd, snappy, lz4), stream processing for large files, and multiple input sources including io.Reader and embed.FS.

## Key Points
- Query flat files with standard SQLite3 SQL — no database server required
- Supports CSV, TSV, LTSV, JSON, Parquet, and Excel (XLSX) formats
- Handles compressed files automatically (.gz, .bz2, .xz, .zst, .snappy, .lz4)
- Stream processing with configurable chunk sizes for large files
- Companion CLI tool: sqly for shell-based SQL queries on files

## Related
- [[golang]] [[sql-driver]] [[sqlite]] [[csv]] [[parquet]] [[data-tools]]
