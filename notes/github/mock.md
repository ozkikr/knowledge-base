---
url: https://github.com/uber-go/mock
type: github-repo
languages: [Go]
tags: [testing, mocking, code-generation, gomock]
date_saved: 2026-02-14
---
# gomock (uber-go/mock) - Mocking Framework for Go

## Summary
gomock is a mocking framework for Go, maintained by Uber after Google abandoned the original golang/mock repo. It integrates with Go's built-in testing package and provides the mockgen tool for generating mock implementations from interfaces.

## Key Points
- Fork of Google's golang/mock, actively maintained by Uber
- mockgen supports three modes: archive, source, and package
- Generates type-safe mock implementations of Go interfaces
- Supports Go's two most recent releases per official release policy
- Integrates with `go:generate` for seamless workflow

## Related
- [[go-testing]]
- [[test-doubles]]
- [[code-generation]]
