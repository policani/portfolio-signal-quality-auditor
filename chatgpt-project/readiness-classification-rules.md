# Readiness Classification Rules

## Purpose

Classify portfolio records so downstream modules receive only the records they are designed to handle.

## Readiness classes

- **Raw demand:** Idea or request exists, but ownership, value, scope, or decision path is unclear.
- **Intake-needed:** Demand is real enough for intake triage, but not ready for scoring.
- **Shaping:** Problem, scope, value, risks, dependencies, or sponsor path needs definition.
- **Ready for scoring:** Record has enough ownership, description, value logic, sizing, risk, dependency, and readiness context for prioritization scoring.
- **Active governed work:** Work is in execution and should be governed through operating cadence.
- **Blocked / decision-needed:** Work cannot progress without a decision, owner action, dependency resolution, or escalation.
- **Parked / deferred:** Work is intentionally paused, deprioritized, or waiting for a future trigger.
- **Closeout / archive candidate:** Work appears complete, obsolete, duplicated, or no longer valid, pending human confirmation.

## Routing rules

- Raw demand and intake-needed items go to Portfolio Intake and Readiness Triage System.
- Ready-for-scoring items go to Portfolio Prioritization Scoring Agent.
- Active governed work and blocked items go to PMO Governance Operations Log for follow-through.
- Executive implications go to Executive Portfolio Review Pack Builder.
- Archive candidates require human confirmation before removal or closure.

## Do not

Do not declare an item ready for scoring when owner, sponsor, scope, value logic, or status is materially unclear.
