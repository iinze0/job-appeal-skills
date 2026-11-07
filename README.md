# Job Appeal Skills

A collection of agent skills for **rigorous review**, **architecture thinking**, and **security analysis**.

Compatible with Claude Code, Cursor, Codex, and other agents that support the open [Agent Skills](https://agentskills.io) standard (SKILL.md).

## Skills

| Skill | Focus |
|-------|--------|
| [rigorous-code-review](./skills/rigorous-code-review/SKILL.md) | Perform a rigorous, structured code review focused on correctness, architecture, security, maintainability, and edge cases |
| [architecture-review](./skills/architecture-review/SKILL.md) | Review software architecture or significant design changes for structural quality, trade-offs, scalability, and long-term risk |
| [security-thinking](./skills/security-thinking/SKILL.md) | Apply rigorous security thinking |
| [test-review](./skills/test-review/SKILL.md) | Review tests for coverage quality, edge cases, flakiness risk, and whether they actually protect the intended behavior |
| [api-design-review](./skills/api-design-review/SKILL.md) | Review API design for consistency, usability, error handling, versioning, and long-term maintainability |
| [performance-review](./skills/performance-review/SKILL.md) | Review code or designs for performance issues, inefficient algorithms, unnecessary work, and scalability bottlenecks |
| [error-handling-review](./skills/error-handling-review/SKILL.md) | Review error handling for completeness, clarity, recovery strategies, and whether failures are handled safely |
| [dependency-review](./skills/dependency-review/SKILL.md) | Review dependencies for security risk, maintenance status, license issues, and whether they are necessary |
| [observability-review](./skills/observability-review/SKILL.md) | Review logging, metrics, tracing, and alerting for usefulness in production |
| [concurrency-review](./skills/concurrency-review/SKILL.md) | Review concurrent code for race conditions, deadlocks, shared state issues, and correctness under parallel execution |
| [data-model-review](./skills/data-model-review/SKILL.md) | Review data models, schemas, or database designs for correctness, normalization trade-offs, query patterns, and migration risk |
| [config-review](./skills/config-review/SKILL.md) | Review configuration management for safety, clarity, environment handling, and secret management |
| [refactor-review](./skills/refactor-review/SKILL.md) | Review refactoring changes to ensure behavior is preserved, complexity is reduced, and the change is justified |
| [naming-and-clarity](./skills/naming-and-clarity/SKILL.md) | Review naming, structure, and clarity of code |
| [migration-review](./skills/migration-review/SKILL.md) | Review database or data migrations for safety, reversibility, performance, and downtime risk |
| [auth-review](./skills/auth-review/SKILL.md) | Review authentication and authorization logic for correctness, privilege escalation risks, and secure defaults |
| [frontend-review](./skills/frontend-review/SKILL.md) | Review frontend code for accessibility, performance, state management, and UX edge cases |
| [ci-review](./skills/ci-review/SKILL.md) | Review CI/CD pipelines for reliability, security, speed, and correctness |
| [documentation-review](./skills/documentation-review/SKILL.md) | Review documentation, comments, and READMEs for accuracy, completeness, and usefulness |
| [release-readiness](./skills/release-readiness/SKILL.md) | Assess whether a change or feature is ready to ship |

## Installation

```bash
npx skills add iinze0/job-appeal-skills
```

Or install a single skill:

```bash
npx skills add iinze0/job-appeal-skills --skill rigorous-code-review
```

## Philosophy

- High-signal findings over volume
- Explain impact, not just problems
- Focus on correctness, architecture, security, and long-term quality
- Practical and proportional recommendations

## License

MIT
