---
url: https://github.com/BookOfCooks/blog/blob/master/htmx-is-hard-so-lets-get-it-right.md
type: article
tags: [htmx, go, web-development, forms, state-management]
date_saved: 2026-02-14
---
# HTMX is Hard, So Let's Get It Right (Part 1)

## Summary
A blog post that builds a multi-step "Soundtrack Uploader" form using HTMX and Go (templ), demonstrating that while HTMX is great, some real-world use cases like complex state management are harder than with traditional frameworks. Part 1 establishes the basics of multi-step form swapping.

## Key Points
- Builds a stepper form where each step POSTs to an endpoint and swaps itself with the next form
- Uses Go backend with templ templates and HTMX hx-post/hx-target/hx-swap
- Argues against the notion that HTMX is a "one-stop-shop" for all web state management
- Part of a series — Part 2 covers S3 presigned multipart uploads and non-linear navigation
- Went viral on Reddit and Hacker News

## Related
- [[htmx]]
- [[go-web-development]]
- [[state-management]]
- [[progressive-enhancement]]
