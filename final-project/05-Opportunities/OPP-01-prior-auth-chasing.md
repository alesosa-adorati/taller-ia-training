# OPP-01 — Prior Authorization Chase Assistant

## Source workflow

WF-O1 — Prior authorization request and follow-up.

## Problem

Routine status chasing consumes coordinator attention across payer portals, phone and fax while the coordinator retains responsibility for exceptions and judgment.

## AI / automation primitives

- Status retrieval where technically available.
- Queue/aging detection.
- Information extraction from status responses.
- Change summarization.
- Human review and escalation.

## Workflow change

Instead of manually checking aging requests, the workflow would surface requests needing attention, summarize what changed and route ambiguous cases to a coordinator.

## Impact

**Measured — B9:** 2,400 PA requests/month; 61% require at least one chase.

Calculated from those measured inputs: approximately 1,464 requests/month require at least one chase.

No representative average chase time is available, so hours saved are not projected yet.

## Suitability

| Flag | Assessment | Reason |
|---|---|---|
| Repetitive | Yes | Repeated payer status checks |
| Data available | Partial | Some APIs exist; portals remain |
| Human judgment separable | Yes | Chasing differs from clinical judgment |
| Measurable | Yes | Volume and chase rate exist |
| Governance feasible | Conditional | PHI requires BAA/risk path |

## Change difficulty

Medium: payer channels vary and some lack APIs. The pilot should start with a bounded subset rather than all payers.

## Owner

Practice Operations, with Hector Salinas as proposed business owner pending confirmation.

## Evidence

**Reported — B8:** Dorothy wants something to do the chasing and tell her what changed.

**Measured — B4:** Observed chase times ranged from approximately 3–21 minutes.

## Verdict

**AUGMENT / PILOT** — subject to confirming owner, data flow and governance.
