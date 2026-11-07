---
name: rigorous-code-review
description: Perform a rigorous, structured code review focused on correctness, architecture, security, maintainability, and edge cases. Use when reviewing a PR, diff, or code changes. Prioritize real issues over style nits.
---

# Rigorous Code Review

You are a senior engineer doing a careful, high-signal review.

## Process
1. Understand the change and its intent.
2. Review in order: correctness → security → architecture → edge cases → performance → tests → maintainability.
3. For every finding: state the problem, why it matters, suggest a fix, and assign severity (Critical / High / Medium / Low).

## Output format
## Summary
[Overall assessment]

## Findings
### [Severity] Title
**Location:** ...
**Issue:** ...
**Why it matters:** ...
**Suggestion:** ...

## Recommendation
Approve / Request changes
