---
url: https://github.com/tummychow/git-absorb
type: github-repo
languages: [Rust]
tags: [git, workflow, fixup, rebase]
date_saved: 2026-02-14
---
# git-absorb

## Summary
A port of Facebook's `hg absorb` for Git. Automatically identifies which staged changes belong to which commits and creates fixup commits, eliminating the need to manually find commit SHAs for `git commit --fixup` or run interactive rebases.

## Key Points
- Automatically maps uncommitted changes to the correct draft ancestor commits
- Creates `fixup!` commits that can be autosquashed with `git rebase --autosquash`
- Supports `--and-rebase` flag for one-step fix-and-rebase workflow
- If changes can't be applied without conflicts, they remain uncommitted
- Ideal for applying code review feedback atomically

## Related
- [[git]] [[interactive-rebase]] [[code-review-workflow]]
