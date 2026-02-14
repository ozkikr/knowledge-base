---
url: https://github.com/walterwanderley/sqlc-gen-go-server
type: github-repo
languages: [Go, SQL]
tags: [sqlc, code-generation, grpc, http-server, protobuf]
date_saved: 2026-02-14
---
# sqlc-gen-go-server

## Summary
An sqlc plugin that generates gRPC, Connect, or HTTP servers directly from SQL queries. Define your schema and queries in SQL, and the plugin generates a fully functional Go server with customizable HTTP endpoints.

## Key Points
- Supports three server types: gRPC, Connect (connectrpc), and HTTP (net/http)
- Custom HTTP endpoints via SQL comments (e.g., `-- http: GET /authors`)
- Distributed as a WASM plugin for sqlc v1.25.0+
- Supports pgx/v5 and other SQL packages
- Related tools: sqlc-http, sqlc-grpc, sqlc-connect for simpler workflows

## Related
- [[sqlc]] - the SQL compiler this plugin extends
- [[structtag]] - Go struct field tag manipulation
