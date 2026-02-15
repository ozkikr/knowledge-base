---
url: https://swizec.com/blog/you-may-be-looking-for-a-useSyncExternalStore/
type: article
tags: [react, hooks, performance, ssr]
date_saved: 2026-02-15
---
# You may be looking for a useSyncExternalStore
## Summary
Technical blog post explaining when to replace `useEffect` + `useState` subscription patterns with `useSyncExternalStore` to reduce hydration jank and improve SSR behavior.

## Key Points
- Identifies a common anti-pattern: effect-driven subscriptions that force extra render cycles.
- Explains hydration jank from client-only subscription setup after server render.
- Demonstrates `useSyncExternalStore` with explicit subscribe/getSnapshot/getServerSnapshot.
- Shows how this pattern improves synchronization with external sources and SSR defaults.
- Encourages selecting better server-side defaults to minimize UI mismatch.

## Related
- React hydration performance
- External store subscriptions
- SSR/CSR consistency
