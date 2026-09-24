# WF-O2 — Referral Intake and Data Entry

## Owner and trigger

**Owner:** Practice Operations / referral intake.

**Trigger:** Incoming referral arrives by fax, portal or post.

## Current-state steps

1. **Human:** Receive referral.
2. **Human:** Open/read source document.
3. **Human:** Determine whether referral information is complete.
4. **Human:** Search the referral lookup spreadsheet when needed.
5. **Human:** Key referral data into Caregate.
6. **Human:** Resolve missing insurance or ambiguous information.
7. **Human:** Save/route referral for downstream processing.
8. **Human:** Apply urgency or exception judgment.

## Volume and channel

**Measured — B9:** 5,800 referrals/month.

**Measured — B9:** 62% arrive by fax.

**Reported — B3:** Aaron estimates approximately 25% are problematic.

## Observed timing

**Measured — B4:** Clean observed faxes took approximately 4m40s and 5m20s, while other clean examples were 4–7 minutes.

**Measured — B4:** One problematic referral required 6 minutes of hold and 16 minutes total.

**Measured — B4:** A handwritten referral took 13 minutes.

## Inputs

Referral document, insurance information, patient information, referring practice and urgency information.

## Outputs

Structured referral in Caregate, routing decision and exception/follow-up work.

## Exceptions

- Handwritten/poor-quality documents.
- Missing insurance.
- Ambiguous urgency.
- Missing fields.
- Lookup required.
- Source information inconsistent.

## Human judgment boundary

Typing and structured extraction are candidates for assistance. Determining urgency, resolving ambiguous information and final verification remain human responsibilities.

## Evidence limitations

**Reported — B3:** Referral keying error rate is unknown. Survey and shadowing do not establish an error baseline.
