---
url: https://antonz.org/chans/
type: article
tags: [go, concurrency, channels, pipelines, generics]
date_saved: 2026-02-14
---
# Building Blocks for Idiomatic Go Pipelines

## Summary
Introduces the `chans` Go package offering generic channel operations for building concurrent pipelines. The library provides composable, unopinionated primitives like Filter, Map, Reduce, chunking, windowing, and fan-out/fan-in without over-abstracting.

## Key Points
- Classic operations: Filter, Map, Reduce over channels
- Filtering/sampling: Drop, Take, TakeWhile, TakeNth, First
- Batching/windowing: Chunk, ChunkBy, Flatten
- Designed to be composable and not take control away from the developer
- Uses Go generics for type safety

## Related
- [[go-concurrency]]
- [[channels]]
- [[functional-programming]]
