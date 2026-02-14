---
url: https://github.com/nkzw-tech/fate
type: github-repo
languages: [TypeScript]
tags: [react, trpc, data-fetching, relay-inspired, normalized-cache]
date_saved: 2026-02-14
---
# fate - Modern Data Client for React & tRPC

## Summary
fate is a modern data client for React and tRPC inspired by Relay and GraphQL. It combines view composition, normalized caching, data masking, Async React features, and tRPC's type safety — without a DSL or GraphQL dependency.

## Key Points
- View composition: components declare co-located data requirements, composed into single requests per screen
- Normalized cache keyed by global identifiers — avoids stale/duplicated data
- Data masking enforces strict selection, preventing accidental coupling between components
- Built-in connection-style pagination with cursor-based infinite scrolling
- Declarative optimistic updates with automatic rollback on failure

## Related
- [[streamdown]] - Another React library from the ecosystem
