---
name: dependency-review
description: Review dependencies for security risk, maintenance status, license issues, and whether they are necessary. Use when adding or auditing third-party packages. Prefer fewer, well-maintained dependencies.
---

# Dependency Review

Evaluate third-party code critically. Prefer removing or replacing risky or unnecessary dependencies.

## Assess
- Known vulnerabilities (if information is available)
- Maintenance activity and bus factor
- License compatibility
- Bundle size or attack surface increase
- Whether the dependency is necessary or could be replaced with a simpler solution
- Transitive dependency risk

## Output format

## Risk summary
[Overall assessment of the dependency set.]

## Specific concerns
### Dependency name
**Issue:** ...
**Risk level:** High / Medium / Low
**Recommendation:** Keep / Replace / Remove / Pin

## Recommendations
[Prioritized actions.]
