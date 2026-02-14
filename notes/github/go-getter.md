---
url: https://github.com/hashicorp/go-getter
type: github-repo
tags: [go, download, hashicorp, terraform]
date_saved: 2026-02-14
---
# go-getter

## Summary
go-getter is a Go library for downloading files or directories from various sources using a URL as input. It supports multiple protocols (file paths, Git, HTTP, Mercurial, etc.) and includes automatic URL detection (e.g., "github.com/user/repo" becomes a Git URL). Used by Terraform and Nomad.

## Key Points
- Download files/directories from multiple sources via a single URL string
- Supports Git, HTTP, Mercurial, S3, GCS, file paths, and more
- Automatic URL detection ("detectors") for shorthand URLs
- Used by Terraform for modules and Nomad for binaries
- Includes security mitigations for SSRF and path traversal

## Related
- [[terraform]] - Primary consumer of this library
- [[nomad]] - HashiCorp job scheduler
- [[go-libraries]] - Go ecosystem tools
