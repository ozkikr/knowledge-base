---
url: https://steipete.me/posts/2025/understanding-codebases-with-ai-gemini-workflow
type: article
tags: [ai-workflow, gemini, code-comprehension, software-design, claude-code]
date_saved: 2026-02-14
---
# My AI Workflow for Understanding Any Codebase

## Summary
Peter Steinberger shares his workflow for understanding codebases and building new projects using AI. The process involves converting repos to markdown with repo2txt, loading them into Google AI Studio with Gemini's large context window, then using a "two-context technique" to iteratively refine Software Design Documents before handing off to Claude Code for implementation.

## Key Points
- Use repo2txt to convert GitHub repos to markdown, then load into Google AI Studio
- "Two-context technique": use a second Gemini context to critique the SDD, feed back to original
- After 3-5 rounds of critique, questions become increasingly niche—signal the spec is solid
- Save final spec as docs/spec.md, then prompt Claude Code with "Build spec.md"
- Skip tests and images when converting repos; include docs and source code

## Related
- [[AI Coding Workflows]]
- [[Gemini]]
- [[Claude Code]]
- [[Software Design Documents]]
