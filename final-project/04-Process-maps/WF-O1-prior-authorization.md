# WF-O1 — Prior Authorization Request and Follow-up

## Owner and trigger

**Owner:** Practice Operations / prior authorization coordination.

**Trigger:** A service requires payer prior authorization.

## Current-state steps

1. **Human — clinic/coordinator:** Receive request and supporting information.
2. **Human/system — coordinator:** Enter or verify information in Caregate.
3. **Human:** Submit through the applicable payer portal, fax or phone path.
4. **Human:** Record status in the PA tracker.
5. **Human:** Monitor aging requests.
6. **Human:** Chase payer when a request exceeds the expected threshold.
7. **Human:** If payer says request was not received, re-submit.
8. **Human:** If information is missing, contact clinic.
9. **Human:** Review exceptions and apply operational/clinical judgment.
10. **Human:** Communicate status to relevant staff.

## Observed timing

**Measured — B4:** One payer chase included a 13-minute phone hold and took 21 minutes total.

**Measured — B4:** Portal-based follow-ups took approximately 3–6 minutes in observed examples.

**Measured — B4:** Three observed new requests took 19, 14 and 17 minutes.

**Measured — B4:** The tracker had 34 rows due for chase at observation start.

## Monthly volume

**Measured — B9:** 2,400 PA requests/month.

**Measured — B9:** 61% require at least one chase.

**Measured — B9:** 18% are initially denied.

## Inputs

- Service/request details.
- Payer and plan.
- Supporting clinical information.
- CPT and related authorization data.
- Existing payer requirements.
- Status history.

## Outputs

- Submitted authorization.
- Status update.
- Escalation or clinic follow-up.
- Approval/denial information.
- Updated tracker record.

## Exceptions

- Payer claims request was never received.
- Missing clinical information.
- Portal rejection.
- Payer rule changes.
- Authorization exists but is not attached to downstream claim.
- Patient-impacting delay.

## Workarounds

**Reported — B3/B7:** The personal tracker contains long-running rules and workarounds.

**Measured — B4:** Re-faxing was used after a payer reported no receipt.

## Human judgment boundary

Status retrieval, aging detection and routine chasing appear suitable for augmentation. Clinical interpretation, exception handling and patient-impact decisions require human review.

## Evidence limitations

The observed sample is one shadowing session and does not establish the full distribution of work types.
