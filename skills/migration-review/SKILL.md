---
name: migration-review
description: Review database or data migrations for safety, reversibility, performance, and downtime risk. Use when reviewing schema changes or data migrations. Focus on production safety.
---

# Migration Review

Ensure migrations are safe to run in production.

## Check
- Locking and downtime risk
- Reversibility or clear rollback plan
- Data correctness during and after migration
- Performance on large tables
- Backfill strategy for existing data
- Order of operations and intermediate states

## Output format

## Risk level
[Low / Medium / High and why.]

## Concerns
### Title
**Issue:** ...
**Impact:** ...
**Safer approach:** ...

## Recommendation
[Go / Go with changes / Do not run yet.]
