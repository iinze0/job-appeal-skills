---
name: api-design-review
description: Review API design for consistency, usability, error handling, versioning, and long-term maintainability. Use when designing or reviewing APIs, endpoints, GraphQL schemas, or public interfaces. Focus on decisions that affect clients long-term.
---

# API Design Review

Evaluate public interfaces for quality and future-proofing.

## Check
- Naming consistency and clarity
- Error responses and status codes (actionable, not leaking internals)
- Idempotency and safety of operations
- Pagination, filtering, and sorting patterns
- Versioning strategy and breaking-change risk
- Authentication and authorization placement
- Documentation and examples quality

## Process
1. Understand the intended consumers and use cases.
2. Review consistency with existing APIs in the system.
3. Flag choices that will force client changes later.
4. Suggest simpler or more consistent alternatives when clear.

## Output format

## Strengths
- [What is well designed]

## Issues
### [Severity] Title
**Area:** Endpoint / field / pattern
**Problem:** ...
**Impact on clients:** ...
**Recommendation:** ...

## Compatibility notes
[Breaking changes, versioning advice, or migration considerations.]
