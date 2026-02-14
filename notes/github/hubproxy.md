---
url: https://github.com/cased/hubproxy
type: github-repo
languages: [Go]
tags: [github, webhooks, proxy, event-replay, reliability]
date_saved: 2026-02-14
---
# HubProxy

## Summary
HubProxy is a proxy for GitHub webhooks designed for teams building with GitHub at scale. It provides webhook verification, event persistence (SQLite/PostgreSQL/MySQL), replay capabilities, and a REST API for querying historical events. Built to ensure no webhooks are lost due to outages or bad deploys.

## Key Points
- Cryptographically verifies GitHub webhook signatures (HMAC) and GitHub IP origins
- Stores webhook events in a database with full replay support (individual or time-range)
- REST API for listing, filtering, and querying events by type, repository, sender, and time range
- Supports SQLite (dev default), PostgreSQL 14+, and MySQL 8+ for production
- Horizontally scalable architecture with webhook handler, storage layer, and API server

## Related
- [[building-blocks-for-idiomatic-go-pipelines]]
- [[good-api-design]]
