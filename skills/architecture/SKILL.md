---
name: architecture
description: Review software architecture or significant design changes for structural quality, trade-offs, scalability, failure modes, and long-term risk. Use for architecture reviews, design docs, or major system changes. Focus on decisions that will be expensive to reverse.
---

# Architecture Review (legacy)

Evaluate design decisions for long-term consequences. Prefer clarity and evolvability over cleverness.

## Dimensions to examine
- **Boundaries & modularity** — Are responsibilities clear? Can parts change independently?
- **Data ownership & flow** — Who owns the data? Where are the sources of truth?
- **Coupling & cohesion** — Tight coupling that will hurt later? Leaky abstractions?
- **Scalability & failure modes** — What happens under load, partial failure, or network issues?
- **Operational complexity** — How hard is this to run, observe, and debug in production?
- **Evolvability** — How expensive will the next 3 changes be?

## Process
1. Summarize the proposed design in your own words.
2. Identify the key decisions and their trade-offs.
3. Flag decisions that are hard to reverse or create hidden coupling.
4. Suggest alternatives only when they clearly reduce risk or cost.

## Severity
- **High** — Structural problem that will cause significant pain or rework.
- **Medium** — Trade-off that should be explicit or mitigated.
- **Low** — Improvement opportunity.

## Output format

## Overview
[What the design is trying to achieve and the main approach.]

## Strengths
- [Clear positives]

## Concerns
### [Severity] Title
**Decision / Area:** ...
**Risk:** What can go wrong and when.
**Recommendation:** How to reduce the risk or make the trade-off explicit.

## Summary judgment
[Is this a sound direction? What must be addressed before proceeding?]
