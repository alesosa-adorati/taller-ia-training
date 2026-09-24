# WF-O1 Swimlane — Prior Authorization

```text
Clinic            Coordinator             Payer / Portal          Caregate / Tracker
  |                     |                       |                       |
  |-- request --------->|                       |                       |
  |                     |-- verify ----------->|                       |
  |                     |-- submit ------------------------------------>|
  |                     |                       |                       |
  |                     |<------ status / request for info -------------|
  |                     |                       |                       |
  |                     |-- chase ------------>|                       |
  |                     |<-- status / no receipt                       |
  |                     |-- re-fax ----------->|                       |
  |                     |                       |                       |
  |<-- clinic follow-up -|                       |                       |
  |                     |                       |                       |
  |                     |-- judgment / escalation                       |
  |                     |---------------------- update ---------------->|
```

## Handoff and wait observations

- Coordinator ↔ payer is the main repeated handoff.
- Clinic follow-up introduces an additional dependency.
- Phone hold creates elapsed time that is not equivalent to active work.
- Tracker updates create a parallel record outside the core systems.

**Measured — B4:** One observed payer interaction had a 13-minute hold and 21-minute total elapsed time.

The diagram is a workflow aid, not a claim that every request follows every branch.
