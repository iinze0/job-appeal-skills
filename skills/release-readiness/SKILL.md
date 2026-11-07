---
name: release-readiness
description: Assess whether a change or feature is ready to ship. Check tests, observability, rollback, and risk. Use before releases or major merges. Prefer clear go/no-go with specific blockers.
---

# Release Readiness Review

Decide if something is safe to ship.

## Checklist
- Tests covering the changed behavior
- Observability (logs/metrics) for the new path
- Rollback or feature-flag plan
- Known risks documented
- Performance impact considered
- Security review if relevant
- Migration safety if data changes

## Output format

## Ready / Not ready
[Clear judgment.]

## Blockers
- [Must-fix items]

## Nice-to-haves
- [Improvements that are not blockers]

## Residual risks
[Accepted risks for this release.]
