---
name: error-handling-review
description: Review error handling for completeness, clarity, recovery strategies, and whether failures are handled safely. Use when reviewing try/catch, Result types, error propagation, or failure paths. Focus on paths that can leave the system in a bad state.
---

# Error Handling Review

Ensure failures are handled deliberately and do not leave the system in a worse state.

## Check
- Unhandled error paths that can crash or corrupt state
- Swallowed errors that hide problems
- Poor or missing error messages
- Missing retries, timeouts, or circuit breakers where appropriate
- Partial failure modes and cleanup
- User-facing vs internal error distinction

## Process
1. Trace the main failure paths.
2. Identify places where errors are ignored or mishandled.
3. Assess recovery and observability of failures.
4. Recommend specific improvements.

## Output format

## Gaps
### Title
**Path:** ...
**Current behavior:** ...
**Risk:** ...
**Recommendation:** ...

## Overall assessment
[How well failures are handled.]
