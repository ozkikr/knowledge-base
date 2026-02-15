---
url: https://cludden.github.io/protoc-gen-go-temporal/docs/configuration/activity
type: article
tags: [temporal, protobuf, go, workflow-engines, configuration]
date_saved: 2026-02-15
---
# Activity | protoc-gen-go-temporal
## Summary
A focused configuration reference for defining Temporal Activities using protobuf annotations in `protoc-gen-go-temporal`. It documents timeout semantics, retry policy fields, naming behavior, cancellation handling, and task queue overrides with concrete examples. Useful as a quick implementation guide when generating Temporal integrations from proto service definitions.

## Key Points
- Activities are declared via `temporal.v1.activity` options on RPC methods.
- Clarifies required timeout combinations: schedule-to-close, schedule-to-start, or start-to-close.
- Supports activity-level retry policy customization (attempts, intervals, backoff, non-retryable errors).
- Documents operational flags like heartbeat timeout and wait-for-cancellation behavior.
- Allows per-activity task queue and type-name overrides beyond service defaults.

## Related
- [[temporal]]
- [[protobuf-options]]
- [[go-workflows]]
