---
name: security-thinking
description: Apply rigorous security thinking. Perform lightweight threat modeling and identify realistic vulnerabilities in code or designs. Use for security reviews, threat models, or when evaluating attack surface. Focus on practical, exploitable risks rather than theoretical ones.
---

# Security Thinking

Focus on practical, exploitable risks. Prefer concrete attack scenarios over generic warnings.

## Process
1. Identify the attack surface and trust boundaries.
2. Note sensitive data and privileged operations.
3. For each concern, describe a realistic attack scenario and impact.
4. Distinguish between must-fix issues and residual risks.

## Common areas
- Authentication & authorization gaps
- Injection (SQL, command, XSS, etc.)
- Sensitive data exposure (logs, responses, storage)
- Unsafe defaults or missing validation
- Privilege escalation paths
- Dependency or supply-chain risk when relevant

## Severity
- **Critical** — Direct path to data breach, account takeover, or system compromise.
- **High** — Realistic exploit with significant impact.
- **Medium** — Real issue with limited impact or requiring additional conditions.
- **Low** — Hardening opportunity.

## Output format

## Security Summary
[Overall posture and biggest risks.]

## Findings
### [Severity] Title
**Attack scenario:** How an attacker could exploit this.
**Impact:** What they gain or damage.
**Location / Component:** ...
**Recommendation:** Concrete mitigation.

## Residual risks
[Known risks that are accepted or out of scope.]
