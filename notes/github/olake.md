---
url: https://github.com/datazip-inc/olake
type: github-repo
tags: [data-ingestion, apache-iceberg, cdc, etl, lakehouse]
date_saved: 2026-02-14
---
# OLake

## Summary
OLake is a high-performance open-source data ingestion engine for replicating databases, S3, and Kafka into Apache Iceberg or plain Parquet. It supports PostgreSQL, MySQL, MongoDB, Oracle, DB2, MSSQL, Kafka, and S3 sources with blazing-fast performance.

## Key Points
- Full + CDC replication with automatic schema discovery and evolution
- 580K RPS for Postgres, 338K RPS for MySQL — claims 12.5× faster than Fivetran for Postgres
- Iceberg-native with support for Glue, Hive, JDBC, REST catalogs
- No Spark, Flink, Kafka, or Debezium required — lightweight infrastructure
- Self-serve UI via Docker Compose; Arrow writes with exactly-once delivery

## Related
- [[apache-iceberg]]
- [[data-lakehouse]]
- [[change-data-capture]]
