# Signal Quality Rules

## Finding severity

Use four severities:

- **Critical:** Materially impairs executive reporting or downstream decision-making.
- **High:** Likely to create wrong conclusions, missed accountability, duplicate work, or bad prioritization.
- **Medium:** Creates ambiguity, rework, or avoidable follow-up.
- **Low:** Formatting or hygiene issue that should be cleaned but does not block review.

## Core rules

1. Missing owner or sponsor is at least High when work is active, blocked, funded, or near a decision point.
2. Missing last update date is High when status is Active, On Track, Blocked, At Risk, or In Progress.
3. Target dates in the past with active status are High unless the record explains why.
4. Conflicting status fields are High when one field implies active work and another implies parked, closed, or blocked.
5. Duplicate-demand candidates are not confirmed duplicates until a human validates scope, sponsor, and intended outcome.
6. KPI fields without definitions, baselines, targets, owners, or measurement cadence are KPI hygiene concerns.
7. Records with unclear readiness should not be sent to prioritization scoring without classification.
8. Rows with no owner, sponsor, date, or next step should be treated as low-trust demand until clarified.

## Confidence labels

Use confidence labels:

- **High confidence:** Finding is directly supported by fields provided.
- **Medium confidence:** Finding is supported by multiple signals but needs human confirmation.
- **Low confidence:** Finding is plausible but data is incomplete.

Do not convert low-confidence findings into definitive claims.
