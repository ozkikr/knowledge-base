---
url: https://swizec.com/blog/in-praise-of-the-stacked-pull-request/
type: article
tags: [software-engineering, code-review, productivity]
date_saved: 2026-02-15
---
# In praise of the stacked pull request
## Summary
This article argues that review throughput is a key bottleneck for team velocity, and that stacked pull requests are a practical way to keep work moving. Instead of one large, hard-to-review change, engineers can submit a sequence of small dependent PRs. The approach improves review quality, reduces testing burden per PR, and preserves momentum during async collaboration.

## Key Points
- Large PRs overwhelm reviewers and slow delivery through review queue bottlenecks.
- Stacked PRs break larger initiatives into independently reviewable slices with explicit dependencies.
- Teams can merge stacks incrementally while preserving logical sequencing.
- Tooling like Graphite can automate stack management and rebasing.
- Smaller review units improve comprehension, confidence, and cycle time.

## Related
- [[stacked-prs]]
- [[trunk-based-development]]
- [[theory-of-constraints]]
