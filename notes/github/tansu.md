---
url: https://github.com/tansu-io/tansu
type: github-repo
languages: [Rust]
tags: [kafka, streaming, data-infrastructure]
date_saved: 2026-02-15
---
# Tansu
## Summary
Tansu is an Apache Kafka-compatible broker implementation with multiple storage backends including PostgreSQL, libSQL/SQLite, S3, and in-memory mode. It supports schema-backed topics and data lake interoperability with Iceberg and Delta Lake outputs. The project is designed as a compact broker + CLI toolkit distribution.

## Key Points
- Provides Kafka API compatibility for producer/consumer and broker workflows.
- Supports several persistence engines for different durability and deployment tradeoffs.
- Adds schema validation paths (JSON Schema, Avro, Protobuf) and lake-oriented output options.
- Bundles broker, topic management, and produce/consume CLI commands in one binary.
- Includes metrics exposure and proxy components for operational environments.

## Related
- [[Apache Kafka]]
- [[Data Lakehouse]]
- [[Event Streaming]]
