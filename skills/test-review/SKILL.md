---
name: test-review
description: Review tests for real coverage of critical paths, edge cases, and failure modes. Assess whether tests actually protect the intended behavior or are mostly noise. Use when reviewing test code or evaluating if a change is adequately tested.
---

# Test Review

Assess whether the tests give real confidence. Prefer tests that fail when behavior breaks over high coverage numbers.

## Look for
- Critical paths or edge cases with no coverage
- Tests that would still pass if the implementation was wrong
- Over-mocking that hides integration issues
- Flaky patterns (timing, shared state, non-deterministic assertions)
- Missing negative tests or error-path coverage
- Tests that only check happy path

## Process
1. Identify the behavior that should be protected.
2. Map existing tests to that behavior.
3. Flag gaps that would allow regressions.
4. Note tests that are brittle or low-value.

## Output format

## Coverage assessment
[What is well protected and what is not.]

## Gaps
### Title
**Missing behavior:** ...
**Risk if untested:** ...
**Suggested test:** Concrete example or outline.

## Recommendations
[Priority order of improvements.]
