# Stale Status Screen

## Purpose

Identify records where the reported status may no longer reflect current reality.

## Inputs

- Status
- Last updated date
- Target date
- Next milestone
- Notes, blockers, or dependencies

## Staleness indicators

Flag records when:

- Status is active but last update is older than the governance cadence.
- Target date or milestone is in the past and status remains active, on track, or in progress.
- Status is blocked or at risk but no next step, owner, or decision need is visible.
- Status is unchanged across multiple reporting cycles, if history is provided.
- Notes describe waiting, dependency, hold, or blocked while status says active or green.

## Default thresholds

If the user provides no cadence:

- 30+ days since update: Medium concern
- 60+ days since update: High concern
- 90+ days since update: Critical for active executive reporting unless explained
- Past target date with active status: High concern

## Output fields

- Record name
- Current status
- Last update date
- Target date or milestone
- Stale-status flag
- Severity
- Evidence
- Recommended cleanup action
- Human decision needed
