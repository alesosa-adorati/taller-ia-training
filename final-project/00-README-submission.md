# Kestrel Health Group — Final Discovery Project

## Engagement overview

This submission documents an end-to-end discovery engagement for Kestrel Health Group using the Track B self-serve case.

The objective is to move from an initial understanding of the organization through workflow discovery, AI maturity assessment, opportunity identification, recommendation, and pilot planning.

The discovery is intentionally evidence-led. Findings are distinguished from assumptions, reported claims, measurements, and projections.

## Client

**Organization:** Kestrel Health Group
**Engagement track:** Track B — Kestrel self-serve case
**Primary executive sponsor:** Marcus Bell, COO
**Primary business concern:** Cost to collect and administrative workload
**In-scope administrative population:** 473 employees across four departments

## Scope

The discovery covers four administrative departments:

* Revenue Cycle
* Practice Operations
* People / Talent
* Patient Growth

The case evidence includes:

* Company and business context
* Employee survey results
* Stakeholder interviews
* Workflow shadowing
* Workshop findings
* IT and compliance evidence
* Existing operational artifacts
* System-volume data
* Deliberate evidence gaps

## Deliverables

### Phase 0 — Prepare

* `01-Admin/client-brief.md`
* `01-Admin/vocabulary.md`
* `01-Admin/prediction.md`

### Phase 1 — Land and learn

* `02-Stakeholders/stakeholder-map.md`
* `02-Stakeholders/PERSONA-<role>.md`

### Phase 2 — Deep discovery

* `04-Process-maps/WF-<id>-<slug>.md`
* `04-Process-maps/baselines.md`
* `04-Process-maps/swimlane.<png|pdf>`
* `04-Process-maps/verification-log.md`

### Phase 3 — Assess and score

* `05-Opportunities/OPP-<id>-<slug>.md`
* `05-Opportunities/backlog.md`
* `05-Opportunities/matrix.<png|pdf>`
* `05-Opportunities/cross-team-pattern.md`
* `06-Maturity/scorecard.md`

### Phase 4 — Deliver

* `07-Readouts/final-report.md`
* `07-Readouts/readout-outline.md`
* `07-Readouts/readout-recording.<mp4> or link`
* `07-Readouts/hostile-questions.md`

### Phase 5 — Build plan

* `08-Pilot/pilot-spec.md`
* `08-Pilot/golden-set.jsonl`
* `08-Pilot/harness-run.txt`

### Phase 6 — Reflection

* `09-Reflection/decision-log.md`
* `09-Reflection/ai-use-disclosure.md`

## Evidence discipline

Every substantive finding will identify its evidence source.

The discovery will distinguish among:

* **Measured** — directly observed or provided as system data or an observed artifact.
* **Reported** — stated by a stakeholder or supplied as a reported case fact.
* **Projected** — calculated or estimated from documented assumptions.
* **Predicted** — an initial hypothesis recorded before detailed workflow analysis.

Numbers will not be presented as measured facts when the source is only a report, estimate, or projection.

## Important evidence limitations

The Kestrel case contains deliberate discovery gaps that will remain visible in the final analysis.

These include:

* Central Scheduling is not covered by direct observation.
* Practice Operations has a lower survey response rate than the other in-scope departments.
* Revenue Cycle does not have a dedicated shadowing session.
* Credentialing does not have a dedicated shadowing session.
* The rate of existing prior authorizations that are not attached to claims is unknown.
* Referral keying error rate is unknown.
* No clinician was interviewed, so the discovery primarily represents the administrative perspective.

These gaps will not be silently resolved through assumptions.

## Repository structure

```text
final-project/
├── 00-README-submission.md
├── 01-Admin/
├── 02-Stakeholders/
├── 03-Interviews/
├── 04-Process-maps/
├── 05-Opportunities/
├── 06-Maturity/
├── 07-Readouts/
├── 08-Pilot/
└── 09-Reflection/

scripts/
```

## Working principle

The engagement will not begin by assuming that AI is the answer.

The analysis will first establish:

1. What work is actually performed.
2. Who performs it and where ownership sits.
3. Which systems, spreadsheets, portals, and documents are involved.
4. Where time, waiting, rework, errors, and handoffs occur.
5. Which parts require human judgment.
6. Which opportunities are suitable for AI assistance, automation, process improvement, or no change.
7. What evidence is required before recommending a pilot.

The final recommendation will therefore be based on workflow evidence and business impact rather than on the availability of an AI capability.
