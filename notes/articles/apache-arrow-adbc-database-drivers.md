---
url: https://www.confessionsofadataguy.com/apache-arrow-adbc-database-drivers/
type: article
tags: [apache-arrow, adbc, database-drivers, performance, data-engineering]
date_saved: 2026-02-14
---
# Apache Arrow ADBC Database Drivers

## Summary
Overview of Apache ADBC (Arrow Database Connectivity), a modern database driver standard built on Apache Arrow's columnar in-memory format designed to replace or complement ODBC/JDBC. ADBC moves Arrow RecordBatches end-to-end, eliminating row-by-row marshaling overhead.

## Key Points
- ADBC delivers near-COPY performance (~275k rows/sec) with much simpler code than psycopg2+COPY (~194k)
- Arrow already underpins DuckDB, Polars, Spark, DataFusion, Pandas, and Flight SQL
- Eliminates serialization/deserialization overhead by keeping data in Arrow format throughout
- DuckDB still significantly faster (~1.15M rows/sec) in benchmarks
- Represents the natural evolution of adding Arrow at the database driver layer

## Related
- [[apache-arrow]]
- [[duckdb]]
- [[database-drivers]]
- [[data-engineering]]
