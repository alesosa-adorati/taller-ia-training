# Kestrel Health Group — Initial AI Maturity Prediction

## Purpose

This document records the initial AI maturity prediction before completing the detailed workflow analysis and opportunity assessment.

These are hypotheses, not final maturity scores.

The final scorecard will require evidence from workflow observations, interviews, system artifacts, survey data, and governance findings.

## Initial prediction

| Dimension             | Initial prediction | Reasoning before detailed analysis                                                                                                                                                                     |
| --------------------- | -----------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Leadership / Strategy |            2.5 / 5 | Leadership recognizes a significant administrative-cost problem and has explicitly requested discovery, but there is no clear enterprise AI strategy or named AI owner.                                |
| People / Skills       |            2.0 / 5 | Employees are already experimenting with AI, but training is limited and sanctioned administrative use is unclear.                                                                                     |
| Data                  |            2.5 / 5 | Kestrel has structured data in major systems and a monthly denial report, but important operational knowledge is fragmented across spreadsheets and individual employees.                              |
| Tools / Technology    |            2.5 / 5 | Several systems expose APIs or structured interfaces, but the environment also depends heavily on payer portals, fax, spreadsheets, and legacy databases.                                              |
| Governance / Risk     |            1.5 / 5 | There is no identified administrative AI policy and no BAA with a general-purpose AI vendor. PHI-related AI use therefore has a significant governance barrier.                                        |
| Adoption / Usage      |            2.0 / 5 | AI experimentation exists among employees and a previous clinical pilot demonstrated some sustained use, but adoption is inconsistent and much usage occurs outside sanctioned organizational tooling. |

## Evidence behind the prediction

### Leadership / Strategy

**Reported — B1:** The COO has explicitly prioritized cost to collect and understanding administrative workload.

**Reported — B1:** The COO has stated that the conclusion could be to hire fewer people and buy no technology.

**Reported — B1/B6:** Kestrel does not currently have a clearly identified administrative AI owner.

This suggests leadership attention to the problem without evidence yet of a mature AI operating model.

### People / Skills

**Measured — B2 survey:** 51% of survey respondents reported using AI for work.

**Measured — B2 survey:** Only 6% reported receiving AI training.

**Measured — B2 survey:** 71% of AI users reported using a personal, non-Kestrel account.

This suggests practical experimentation without corresponding formal enablement.

### Data

Kestrel has structured systems including Caregate and ClearBridge, but operational knowledge also exists in locally maintained spreadsheets.

**Measured — B7:** The prior-authorization tracker contained 431 rows at observation.

**Measured — B7:** The referral lookup spreadsheet contained approximately 900 rows.

**Reported — B4/B7:** The prior-authorization tracker contains approximately 12 years of rules and workarounds in free-text notes.

This suggests useful data exists but is fragmented and not consistently systematized.

### Tools / Technology

**Reported — B6:** Caregate has a documented read API.

**Reported — B6:** ClearBridge has an API.

**Reported — B6:** RightFax documents are retrievable through an API.

However, Kestrel also depends on seven payer portals, fax, spreadsheets, and uncertain Access databases.

This suggests moderate technical enablement with substantial fragmentation.

### Governance / Risk

**Reported — B6:** Kestrel has no AI usage policy.

**Reported — B6:** There is no BAA with a general-purpose AI vendor.

**Reported — B6:** PHI-bearing AI use requires a BAA and risk assessment, with a minimum estimated governance timeline of 6–8 weeks.

This is the clearest predicted maturity constraint.

### Adoption / Usage

**Measured — B2 survey:** 51% of respondents reported using AI for work.

**Measured — B2 survey:** Among AI users, 9% reported daily use, 19% weekly use, and 72% occasional or rare use.

**Reported — B1:** In the clinical scribe pilot, 12 clinicians continued daily use while 28 stopped within six weeks.

The evidence suggests awareness and experimentation rather than consistent enterprise adoption.

## What would change these predictions

The final assessment should change these predictions if discovery evidence shows:

* stronger or weaker executive ownership than currently documented;
* formal AI governance not captured in the case materials;
* stronger data quality or lineage than the current artifacts suggest;
* additional sanctioned AI tooling;
* higher or lower observed adoption;
* workflow-level evidence that materially changes the current picture.

## Important distinction

These values are **initial predictions only**.

They are not the final Kestrel AI maturity assessment.

The final assessment will be documented in:

`06-Maturity/scorecard.md`

and will include evidence, claim labels, next-level gaps, and the distinction between self-reported and observed behavior where applicable.
