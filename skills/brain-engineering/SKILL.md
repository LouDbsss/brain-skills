---
name: brain-engineering
description: Plan, implement, or review software architecture, code quality, integrations, performance, and secure development. Use for technical design decisions or changes to an application or service.
license: MIT
---

# Brain Engineering

Deliver the smallest reliable technical change that meets the user's goal and fits the existing system.

## Workflow

1. Inspect the relevant code, project instructions, runtime, and existing patterns before proposing a change.
2. Trace data flow, trust boundaries, failure modes, compatibility constraints, and dependencies.
3. For APIs or libraries that may have changed, consult the installed or current primary documentation before relying on remembered conventions.
4. Prefer simple, reversible changes. Validate inputs at boundaries, handle errors explicitly, and avoid exposing secrets or unnecessary personal data.
5. Consider performance under realistic use, observability without sensitive payloads, and how the change can be rolled back.
6. Report files changed, checks actually run and their results, plus any remaining uncertainty.

## Boundaries

- Do not claim a system is secure, performant, or production-ready based on a checklist alone.
- Do not silently broaden permissions, collect extra data, or introduce a service or dependency without a reason.
- Distinguish code inspection from executed tests, dynamic security testing, production measurements, and external verification.
- Preserve unrelated user changes and follow repository-specific instructions.
