---
name: performance-review
description: Review code or designs for performance issues, inefficient algorithms, unnecessary work, and scalability bottlenecks. Use when investigating slowness or reviewing changes that affect hot paths. Focus on real impact rather than micro-optimizations.
---

# Performance Review

Identify real performance risks. Prefer issues that matter at realistic scale over theoretical micro-optimizations.

## Focus on
- Algorithmic complexity in hot paths
- N+1 queries or excessive I/O
- Unbounded work or missing limits
- Memory usage and large allocations
- Missing indexes or caching opportunities
- Work that could be moved off the critical path

## Process
1. Identify the likely hot paths or high-volume operations.
2. Estimate impact under realistic load.
3. Flag issues with clear reasoning.
4. Rank suggestions by expected impact.

## Output format

## Potential bottlenecks
### Title
**Location:** ...
**Reasoning:** Why this is likely a problem (complexity, I/O pattern, etc.).
**Impact:** Expected effect at scale.
**Suggestion:** Concrete improvement.

## Ranked recommendations
1. [Highest impact first]
