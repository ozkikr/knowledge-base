---
url: https://github.com/BemiHQ/BemiDB
type: github-repo
languages: [Go]
tags: [analytics, data-warehouse, postgres, s3, columnar-storage]
date_saved: 2026-02-14
---
# BemiDB - Open-Source Snowflake & Fivetran Alternative

## Summary
BemiDB is an open-source alternative to Snowflake and Fivetran, bundling data ingestion and analytical querying. It syncs data from various sources into compressed columnar format on S3 and provides a Postgres-compatible analytical query engine that's 2000x faster than regular Postgres for analytical workloads.

## Key Points
- Analytical query engine with Postgres wire protocol compatibility
- Columnar storage on S3 with 4x data compression using open table format
- Built-in connectors for Postgres, Amplitude, Attio, Dialpad
- Single Docker image deployment with stateless processes
- Powers AI Agent sandbox environments at gettelio.com

## Related
- [[pipeshub-ai]] - enterprise data platform
- [[centrifugo]] - Go infrastructure
