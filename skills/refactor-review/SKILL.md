---
name: refactor-review
description: Review refactoring changes to ensure behavior is preserved, complexity is reduced, and the change is justified. Use when evaluating refactors. Prefer small, safe refactors over large risky ones.
---

# Refactor Review

Verify the refactor improves the code without changing behavior.

## Verify
- Behavior preservation (especially edge cases)
- Actual reduction in complexity or coupling
- Test coverage of the changed area
- Justification for the scope of the change
- Risk of introducing new bugs

## Output format

## Behavior risk
[Assessment of whether behavior is preserved.]

## Quality improvement
[Does this actually make the code better?]

## Recommendation
Approve / Request changes
[Must-fix items if any.]
