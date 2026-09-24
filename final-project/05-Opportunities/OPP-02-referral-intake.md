# OPP-02 — Referral Intake Extraction and Verification

## Source workflow

WF-O2 — Referral intake and data entry.

## Workflow change

Extract structured referral fields from incoming documents and present them for human verification before entry into Caregate.

## Impact

**Measured — B9:** 5,800 referrals/month; 62% arrive by fax.

Calculated fax volume: `5,800 × 62% = 3,596/month`.

**Measured — B4:** Clean examples were approximately 4–7 minutes; problematic examples included 13 and 16 minutes.

No full average is projected.

## Suitability

| Flag | Assessment | Reason |
|---|---|---|
| Repetitive | Yes | Manual extraction/keying |
| Data available | Yes | Source PDFs/faxes |
| Human judgment separable | Yes | Final verification remains human |
| Measurable | Yes | Volume and observed timings |
| Governance feasible | Conditional | PHI requires approved data flow |

## Change difficulty

Medium. RightFax has an API, but source-document quality varies.

## Owner

Practice Operations / referral intake, pending confirmation.

## Evidence

**Reported — B3:** Aaron would hand all typing to an assistant while keeping judgment.

**Measured — B4:** Fax queue observation showed 47 new faxes at the start of shadowing.

## Verdict

**AUGMENT / PILOT CANDIDATE** — validate extraction accuracy before scaling.
