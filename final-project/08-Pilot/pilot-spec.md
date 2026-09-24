# Pilot Specification — Prior Authorization Chase Assistance

## Objective

Test whether routine prior-authorization status chasing can be reduced while preserving human judgment and patient-impact escalation.

## Scope

In scope:
- A bounded subset of prior-authorization requests.
- Aging/status detection.
- Approved status retrieval where technically available.
- Change summarization.
- Human review.
- Audit logging.

Explicit exclusions:
1. No autonomous clinical decision.
2. No autonomous approval/denial decision.
3. No autonomous patient communication.
4. No autonomous submission to payer.
5. No replacement of the existing PA record until validated.
6. No use of PHI with an unapproved vendor/service.

## Baseline

**Measured — B9:** 2,400 PA requests/month; 61% require at least one chase.

**Measured — B4:** Observed chase examples ranged from approximately 3–21 minutes.

Baseline method: sample a defined set of eligible PA requests before pilot start and measure active human chase time, elapsed status time and exception rate.

Baseline date: establish at pilot kickoff.

## Metrics

### Primary

Median active human minutes spent on eligible status-chasing cases.

### Secondary

1. Percentage of eligible cases correctly surfaced for review.
2. Rate of missed or incorrectly escalated patient-impacting cases.

## Roles

- Business owner: Hector Salinas, pending confirmation.
- Workflow SME: Dorothy Kimball.
- Technical owner: Ken, pending confirmation.
- Governance: Sandra Whitlock.
- Executive sponsor: Marcus Bell.

## Data/access plan

- Define minimum-necessary fields.
- Use de-identified data for development where possible.
- Confirm payer/API access with Ken.
- Confirm BAA/risk path with Sandra.
- Confirm production access owner before any PHI test.

## Comparison method

Compare pilot-period eligible cases with a matched pre-pilot baseline using the same case-selection rules.

Weakness: payer mix and case complexity can change over time, so a simple before/after comparison cannot establish causality alone.

## Go/no-go gate

Proceed only if the pilot meets the primary metric target without increasing critical misses or governance violations.

## Kill criteria

Stop the pilot if any of the following occurs:
1. Any confirmed PHI disclosure to an unapproved service.
2. Any critical patient-impacting case is missed because of pilot behavior.
3. Evaluation accuracy falls below the agreed threshold for two consecutive review batches.
4. Audit logs fail for any production-like test batch.
5. Business owner withdraws sponsorship before the scheduled review date.

## Risks

1. Payer-channel variability.
2. Incorrect status interpretation.
3. PHI exposure.
4. Missing patient-impacting cases.
5. Low frontline adoption.
6. Vendor/API contractual constraints.
7. Overestimating savings from small samples.

## No-AI improvement

Before or alongside the pilot, standardize PA chase reason codes and preserve verified payer rules separately from free-text workarounds. This can reduce ambiguity without AI.
