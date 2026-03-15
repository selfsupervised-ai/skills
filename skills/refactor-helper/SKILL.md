---
name: Refactor Helper
description: Suggests and applies refactoring patterns to improve code quality
tags:
  - refactoring
  - quality
  - patterns
---

# Refactor Helper

Analyze the provided code and suggest refactoring improvements:

1. **Identify code smells** - Duplication, long methods, large classes, feature envy, primitive obsession
2. **Suggest refactoring patterns** - Extract method, extract class, introduce parameter object, replace conditional with polymorphism
3. **Apply changes safely** - Preserve existing behavior, maintain test compatibility
4. **Explain trade-offs** - Why the refactoring improves the code and any risks

Priorities:
- Readability over cleverness
- Small, incremental changes over large rewrites
- Maintain backward compatibility unless explicitly told otherwise
- Follow existing project conventions and patterns
