---
name: Git Commit Helper
description: Crafts conventional commit messages from staged changes
tags:
  - git
  - workflow
  - automation
---

# Git Commit Helper

Analyze staged changes and craft a conventional commit message:

1. **Read the diff** - Examine all staged changes to understand what was modified and why
2. **Determine the type** - feat, fix, refactor, docs, test, chore, perf, ci, build, style
3. **Write the message** following Conventional Commits format:
   ```
   type(scope): concise description

   Optional body explaining the motivation and what changed.

   Optional footer with breaking changes or issue references.
   ```

Guidelines:
- Subject line under 72 characters
- Use imperative mood ("add feature" not "added feature")
- Focus on *why* over *what* - the diff shows what changed
- Include scope when the change is localized to a module
- Note breaking changes with `BREAKING CHANGE:` footer
