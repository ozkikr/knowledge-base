---
url: https://gremlins.dev/latest/
type: article
tags: [go, testing, mutation-testing, quality, ci]
date_saved: 2026-02-15
---
# Gremlins
## Summary
Documentation introducing Gremlins, a mutation testing tool for Go aimed at validating test-suite quality and acting as a CI quality gate for smaller services.

## Key Points
- Mutation testing is positioned as a stronger signal than coverage-only metrics.
- Gremlins mutates tested code and checks whether test suites detect the changes.
- The tool is designed for microservice-scale modules and includes CI-oriented workflows.
- Current limitations include long runtimes on very large repositories.

## Related
- [[integration-testing-go-testcontainers-cosmosdb]]
- [[stop-vibe-coding-your-unit-tests]]
