---
url: https://dineshpandiyan.com/blog/stacked-diffs-with-rebase-onto/
type: article
tags: [git, stacked-diffs, rebase, workflow, code-review]
date_saved: 2026-02-14
---
# Stacked Diffs with `git rebase --onto`

## Summary
A practical guide to managing stacked PRs (dependent branches) using `git rebase --onto`. Explains why regular rebase breaks stacked branches (duplicate commits from old hashes), and introduces marker branches to track the old base for clean rebasing.

## Key Points
- `git rebase --onto <new-base> <old-base> <branch>` moves only the right commits
- Create marker branches (e.g., `feature-2-base`) to track old parent state
- Must update marker after each rebase (`git branch -f feature-2-base feature-1`)
- When parent branch merges to main, use `git rebase -i main` to drop old commits
- Stacked diffs enable small, focused, reviewable PRs

## Related
- [[git]]
- [[jj]]
- [[lazygit]]
- [[code-review-workflow]]
