---
url: https://github.com/iqea-ai/duckdb-snowflake
type: github-repo
languages: [C++, Python, Shell, CMake, Makefile, Batchfile]
tags: [duckdb, snowflake, adbc]
date_saved: 2026-02-15
---
# iqea-ai/duckdb-snowflake
## Summary
duckdb-snowflake is a DuckDB extension that enables direct querying of Snowflake through Apache Arrow ADBC drivers. It aims to make cross-system analytics and ETL simpler by keeping transfers columnar and efficient. The repo provides installation instructions, authentication options, and examples for query pass-through and attached read-only Snowflake storage.

## Key Points
- Adds Snowflake connectivity to DuckDB with an Arrow-native transport path.
- Supports multiple auth modes including password, key pair, OAuth, SSO, Okta, and MFA.
- Integrates with DuckDB secrets for credential management.
- Supports query function usage and ATTACH-based read-only database access.
- Documents platform-specific ADBC driver installation and validation steps.

## Related
- [[DuckDB]]
- [[Snowflake]]
- [[Apache Arrow ADBC]]
