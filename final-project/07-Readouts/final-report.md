# Kestrel Health Group — Final Discovery Report

## 1. The discovery covered three deep workflows but leaves explicit evidence gaps.

This Track B discovery reviewed company context, survey evidence, interviews, shadowing, systems and artifacts.

**Measured — B1:** 473 administrative employees are in scope.

The deep-dive workflows were prior authorization, referral intake and denial appeal preparation.

Coverage gaps include no clinician interview, no RCM shadowing, no credentialing shadowing, incomplete central-scheduling coverage, a 20% Practice Operations survey response rate, unknown referral keying error rate and unknown rate of valid authorizations not attached to claims.

## 2. Administrative work is concentrated around chasing, transferring and finding information.

**Measured — B9:** Kestrel processes 2,400 PA requests/month, 5,800 referrals/month and works 3,100 denials/month.

**Measured — B9:** 61% of PA requests require at least one chase and 62% of referrals arrive by fax.

**Measured — B4:** Prior-authorization observation showed payer holds, re-faxing, tracker maintenance and clinic follow-up.

**Measured — B4:** Referral observation showed manual extraction from faxes and lookup spreadsheets.

The evidence indicates significant repetitive information work, but it does not establish total labor hours saved without broader sampling.

## 3. AI maturity is constrained more by governance and operating model than by employee curiosity.

**Measured — B2:** 51% of respondents reported using AI for work, while only 6% reported training.

**Measured — B2:** 71% of AI users reported using personal accounts.

**Reported — B6:** PHI-related AI use requires a BAA and risk assessment with a minimum estimated path of 6–8 weeks.

The resulting maturity score is 3.0 leadership/strategy, 2.5 people/skills, 2.5 data, 2.5 tools/technology, 1.5 governance/risk and 2.5 adoption/usage.

## 4. The opportunity backlog favors augmentation over autonomous replacement.

The six opportunities include three augmentation candidates, one investigation, one lower-priority no-go and one explicit no-go.

The strongest evidence supports prior-authorization chasing, referral extraction/verification and appeal-evidence retrieval.

The patient-balance workflow should not be autonomously automated because the case explicitly describes distress, hardship and judgment after the scripted opening.

## 5. The first roadmap should test two bounded workflow changes before scaling.

### Pilot 1 — Prior authorization chase assistance

Workflow: WF-O1.

Baseline: **Measured — B9:** 2,400 PA requests/month and 61% requiring at least one chase.

Primary success metric: reduce the proportion of sampled eligible PA requests requiring manual status-chasing activity without increasing missed/escalated patient-impacting cases.

Owner: Practice Operations, with Hector Salinas proposed pending confirmation.

First action: confirm owner and select a bounded payer subset with IT and compliance.

### Pilot 2 — Referral extraction and verification

Workflow: WF-O2.

Baseline: **Measured — B9:** 5,800 referrals/month and 62% fax.

Primary success metric: verified extraction accuracy on a controlled golden set while reducing median human entry time.

Owner: Referral Intake / Practice Operations, pending confirmation.

First action: obtain an approved sample of de-identified referral documents and define the verification protocol.

## 6. The next decision requires owners, data access and governance dates.

- **Thing:** Confirm Pilot 1 business owner — **Person:** Hector Salinas — **Date:** before pilot kickoff.
- **Thing:** Confirm PHI/data-flow review path — **Person:** Sandra Whitlock — **Date:** before production-like testing.
- **Thing:** Confirm API/access feasibility — **Person:** Ken — **Date:** before pilot design freeze.
- **Thing:** Approve golden-set creation — **Person:** Pilot owner + compliance — **Date:** before evaluation run.
- **Thing:** Set pilot go/no-go decision date — **Person:** Marcus Bell — **Date:** at executive readout.

## Recommended next step

Proceed with bounded validation, not broad deployment. The next phase should measure the unknowns that materially affect the decision and should retain a no-AI/no-buy path where evidence does not support automation.
