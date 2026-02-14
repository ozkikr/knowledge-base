---
url: https://devblogs.microsoft.com/cosmosdb/integration-testing-for-go-applications-using-testcontainers-and-containerized-databases/
type: article
tags: [go, testing, testcontainers, cosmosdb, docker, integration-testing]
date_saved: 2026-02-14
---

# Integration Testing for Go Applications Using Testcontainers and Containerized Databases

## Summary
A Microsoft DevBlog article demonstrating how to use testcontainers-go with the Azure Cosmos DB emulator for integration testing. Shows how to run real database instances in Docker containers during tests, eliminating the need for mocks or shared test environments.

## Key Points
- Testcontainers spins up lightweight, throwaway Docker containers for real service testing
- testcontainers-go provides idiomatic Go API with lifecycle management, port mapping, and health checks
- Tests against actual technologies used in production while maintaining isolation
- Containers auto-cleanup after tests complete
- Practical example uses Azure Cosmos DB emulator

## Related
- [[testcontainers]] - testing framework for containerized dependencies
- [[cosmosdb]] - Azure's distributed database
- [[go-testing]] - Go's testing ecosystem
