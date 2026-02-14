---
url: https://www.ducktyped.org/p/an-illustrated-guide-to-oauth
type: article
tags: [oauth, authentication, security, web-development]
date_saved: 2026-02-14
---
# An Illustrated Guide to OAuth

## Summary
A visual, beginner-friendly walkthrough of OAuth using the example of YNAB connecting to Chase Bank. Explains why sharing passwords with third parties is dangerous and how OAuth solves this with access tokens — user-specific API keys with scoped permissions.

## Key Points
- OAuth was created at Twitter in 2007 to let third-party apps act on users' behalf without sharing passwords
- The core concept is an access token: a scoped, user-specific credential issued by the resource server
- The flow involves redirect to auth server → user login & consent → redirect back with authorization code → exchange for token
- Access tokens can be scoped to specific permissions (e.g., read-only on one bank account)
- The article walks through the flow twice for clarity, once from user perspective and once showing the backend mechanics

## Related
- [[api-design]]
- [[authentication]]
- [[web-security]]
