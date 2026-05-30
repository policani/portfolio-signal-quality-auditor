# Duplicate Demand Screen

## Purpose

Find possible duplicate or overlapping portfolio records without automatically merging them.

## Candidate signals

Flag possible duplicates when two or more records share:

- Similar initiative names
- Same sponsor or owner
- Same business outcome
- Same system, product, platform, vendor, or process area
- Same milestone, release, regulatory need, or funding request
- Similar description with different statuses
- One record appears to be a renamed or rescoped version of another

## Classifications

- **Likely duplicate:** Same outcome and same work appear to be represented more than once.
- **Possible duplicate:** Similar name, sponsor, or target outcome, but scope may differ.
- **Related work:** Connected initiatives that should remain separate but may need dependency linkage.
- **Not enough information:** Similarity exists but source data is too thin.

## Output fields

- Candidate group
- Records involved
- Similarity evidence
- Why it matters
- Duplicate classification
- Confidence
- Recommended human review question
- Suggested cleanup action

## Guardrail

Never merge, close, rename, or remove records. Recommend review only.
