---
name: Test Writer
description: Generates unit and integration tests with high coverage
tags:
  - testing
  - quality
  - automation
---

# Test Writer

Generate comprehensive tests for the provided code:

1. **Identify testable units** - Functions, methods, classes, and their public APIs
2. **Write unit tests** covering:
   - Happy path with typical inputs
   - Edge cases (empty inputs, boundary values, null/undefined)
   - Error cases (invalid inputs, exceptions, timeouts)
3. **Write integration tests** for cross-module interactions when applicable
4. **Use the project's existing test framework** - Match the style, assertions, and patterns already in use

Guidelines:
- Each test should have a clear, descriptive name explaining what it verifies
- Use arrange-act-assert structure
- Avoid testing implementation details - test behavior
- Mock external dependencies (network, filesystem, databases) unless integration testing
- Aim for meaningful coverage, not 100% line coverage
