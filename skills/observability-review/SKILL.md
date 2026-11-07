---
name: observability-review
description: Review logging, metrics, tracing, and alerting for usefulness in production. Use when evaluating observability or adding instrumentation. Focus on whether operators can actually debug and detect problems.
---

# Observability Review

Check if the system is debuggable and monitorable in production.

## Look for
- Missing logs on important success and failure paths
- Sensitive data in logs
- Useful metrics for key business and technical indicators
- Tracing coverage of critical flows
- Alert quality (signal vs noise)
- Correlation IDs or request context

## Output format

## Current state
[What is well instrumented and what is missing.]

## Gaps
### Area
**Missing:** ...
**Why it matters:** ...
**Suggestion:** ...

## Improvements
[Prioritized list.]
