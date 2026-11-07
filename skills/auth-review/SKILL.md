---
name: auth-review
description: Review authentication and authorization logic for correctness, privilege escalation risks, and secure defaults. Use for auth-related code or design reviews. Focus on realistic escalation paths.
---

# Auth Review

Focus on identity and access control. Prefer fail-closed defaults.

## Check
- Clear separation of authentication and authorization
- Privilege escalation paths
- Token handling, storage, and validation
- Default permissions and least privilege
- Session management and logout
- Missing checks on sensitive operations

## Output format

## Findings
### [Severity] Title
**Attack scenario:** ...
**Impact:** ...
**Location:** ...
**Recommendation:** ...

## Overall assessment
[How solid is the auth design.]
