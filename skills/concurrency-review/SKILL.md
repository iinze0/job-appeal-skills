---
name: concurrency-review
description: Review concurrent code for race conditions, deadlocks, shared state issues, and correctness under parallel execution. Use for multithreaded, async, or distributed concurrent code. Focus on realistic race scenarios.
---

# Concurrency Review

Hunt for concurrency bugs that can appear under load or unlucky timing.

## Check
- Shared mutable state without proper synchronization
- Missing locks or incorrect lock ordering
- Race conditions on check-then-act patterns
- Deadlock potential
- Async error propagation and cancellation
- Assumptions that break under parallel execution

## Output format

## Issues found
### [Severity] Title
**Scenario:** How the race or deadlock can occur.
**Impact:** ...
**Location:** ...
**Fix:** ...

## Residual risks
[Any remaining concerns.]
