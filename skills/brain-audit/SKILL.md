---
name: brain-audit
description: Review a defined change, artifact, or release for quality risks and evidence gaps. Use before delivery to prioritize findings across functionality, security, dependencies, accessibility, and operational readiness.
license: MIT
---

# Brain Audit

Perform a scoped, evidence-led review. Make findings actionable and distinguish observed defects from risks and unknowns.

## Workflow

1. Define the artifact, version, intended behavior, environment, and review scope. State exclusions.
2. Inspect relevant source, configuration, dependencies, tests, and supplied evidence. Do not assume a scanner or test was run.
3. For each finding, record severity, affected area, reproducible evidence, impact, and a practical remediation. Avoid duplicative or speculative findings.
4. Track checks as PASS, FAIL, NOT_VERIFIED, or NOT_APPLICABLE; include method and evidence for each status.
5. Prioritize critical and high-impact issues, then usability and maintainability. Recheck fixes when authorized and report the new evidence.
6. Summarize release blockers, accepted risks, unresolved unknowns, and the exact scope reviewed.

## Boundaries

- A documentary review is not an executed test, penetration test, dependency scan, secret scan, or certification.
- Do not print, copy, or expose secrets found during review; report their location minimally and recommend safe rotation/removal.
- Do not mark a finding resolved without evidence of the fix and an appropriate recheck.
- Do not imply that an artifact review covers the full repository, deployment, or runtime unless it does.
