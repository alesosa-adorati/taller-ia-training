# Kestrel Health Group — Client Brief

## 1. What Kestrel does and how it makes money

Kestrel Health Group is a multi-specialty physician group operating outpatient medical services in North Carolina. Its clinical footprint includes primary care, orthopedics, cardiology, endocrinology and imaging.

**Measured — B1:** Kestrel has 218 clinicians and 31 outpatient sites.

**Reported — B1:** Net patient revenue is $412M, with revenue growing 7% and patient volume growing 5%.

The discovery is focused on Revenue Cycle, Practice Operations, People/Talent and Patient Growth.

**Measured — B1:** The in-scope population is 473 administrative employees.

**Measured — B1:** Cost to collect is 4.1%, compared with a reported peer median of approximately 3.2%.

**Measured — B1:** Days in A/R increased from 41 to 46.

**Measured — B1:** First-pass claim acceptance is below 88%.

**Reported — B1:** Kestrel added 63 administrative employees versus 11 clinicians over the previous two years.

Marcus Bell, COO, has asked the discovery team to understand what the approximately 470 administrative employees do and how much of that work should be performed by a person. His stated priority is cost to collect. He has also said that the answer could be to hire fewer people and buy nothing.

**Source:** B1 Company.

## 2. Kestrel's relationship with AI

Kestrel has experimented with AI, but adoption and governance are inconsistent.

**Reported — B1/B2:** A 2024 ambient-scribe pilot involved 40 clinicians. Twelve continued daily use while 28 stopped within six weeks. No baseline was measured for that pilot.

**Measured — B2:** 51% of survey respondents who answered the AI-use question reported using AI for work.

**Measured — B2:** 71% of those AI users reported using a personal, non-Kestrel account.

**Measured — B2:** Only 6% reported receiving AI training.

**Reported — B2:** The Patient Growth team has four Copilot licenses.

**Measured — B2:** Among AI users, 9% reported daily use, 19% weekly use and 72% occasional or rare use.

Common reported uses were writing/editing, summarization, information lookup and spreadsheet formulas.

**Measured — B2:** 38% identified uncertainty about whether AI use is allowed as a concern; 27% identified privacy and 18% accuracy.

**Reported — B3:** One employee reported that AI hallucinated a nonexistent policy when used for an appeal.

**Reported — B6:** Kestrel has no BAA with a general-purpose AI vendor. Any AI tool handling PHI requires a BAA and risk assessment, with an estimated minimum review period of 6–8 weeks.

The evidence therefore supports the conclusion that employee experimentation exists while controlled organizational adoption remains immature.

**Sources:** B1, B2, B3, B6.

## 3. Working vocabulary

| Term | Plain-language meaning | Why it matters |
|---|---|---|
| Net patient revenue | Revenue generated from patient care after applicable adjustments | Core business outcome |
| Cost to collect | Administrative cost associated with collecting patient and payer revenue | Primary COO priority |
| Days in A/R | Average number of days revenue remains in accounts receivable | Collection-cycle performance |
| First-pass claim acceptance | Percentage of claims accepted without first-submission rejection | Upstream claim quality |
| Prior authorization | Payer approval required before certain services | Major Practice Operations workload |
| Payer | Insurance organization responsible for eligible payment | Determines rules and status |
| Clearinghouse | Service exchanging claims between providers and payers | ClearBridge performs this role |
| Denial | Claim or payment request rejected by a payer | Creates downstream work |
| Appeal | Request for a payer to reconsider a denial | Requires evidence and submission |
| PHI | Protected Health Information | Determines data-handling requirements |
| BAA | Business Associate Agreement | Required for applicable PHI vendors |
| Credentialing | Establishing provider qualifications with payers/organizations | Enables billable care |
| Payer enrollment | Registering a provider with an individual payer | Delays can prevent billing |
| A/R | Accounts receivable | Key revenue-cycle metric |

**Sources:** B1, B3, B6, B9.

## 4. Key people and roles

- Marcus Bell — COO and executive sponsor.
- Sandra Whitlock — compliance/governance stakeholder.
- Tanya Brooks — VP Revenue Cycle.
- Hector Salinas — Director Practice Operations.
- Ken — IT/systems stakeholder.
- Dorothy Kimball — prior authorization coordinator and frontline SME.
- Nia Croft — billing/denials and appeals SME.
- Aaron Petit — referral intake SME.
- Marisol Vega — credentialing lead.
- Wendy Ofori — People Operations.
- Ellis Chang — Patient Growth/marketing.
- Ray Odom — patient balance team.

**Sources:** B1, B3, B6.

## 5. Relevant documentation and systems

Systems include Caregate, ClearBridge, seven payer portals, RightFax/eFax, Sage Intacct, Paylink, HubSpot, SharePoint/OneDrive, Microsoft 365/Excel, Genesys and Access databases.

Available documents include a 2021 Revenue Cycle manual, 2023 front-desk onboarding, organizational charts and a systems inventory.

**Reported — B1:** Prior-authorization and referral documentation is incomplete, and Kestrel has no administrative AI policy.

**Source:** B1, B6, B7.

## 6. Initial discovery hypotheses

The strongest initial hypotheses are:

1. Repetitive administrative chasing is a significant source of avoidable effort.
2. Information is fragmented across spreadsheets, fax, portals and systems.
3. Some work is suitable for augmentation while judgment should remain human.
4. Governance and ownership may constrain AI deployment more than model capability.
5. The best pilot will need a measurable workflow baseline and a named business owner.
6. Some improvements may require no AI at all.

These are hypotheses, not final recommendations.

## 7. Open questions, contradictions, and resolution plan

### 1. How often does an existing prior authorization fail to reach the claim?

**Evidence — Reported — B3/B6:** Nia reported missing prior authorization as a common denial category, while Ken stated that Kestrel does not have a number showing how often an authorization exists but is not attached to a claim.

**Status:** Unknown.

**Resolution plan:** Sample claims with missing or invalid authorization and determine whether an authorization existed but was not attached.

### 2. Is the prior-authorization “never received” rate measurable?

**Evidence — Reported — B3:** Dorothy described requests being reported as never received.

**Evidence — Measured — B4:** One observed request required re-faxing after a payer reported that it had never been received.

**Status:** The observed event is measured; the broader rate is unknown.

**Resolution plan:** Sample recent chases and classify the reason for each chase.

### 3. How accurate is referral data entry?

**Evidence — Reported — B3:** Aaron stated that referral keying error rate is unknown.

**Status:** Unknown.

**Resolution plan:** Audit entered referrals against source documents and separate transcription errors from source ambiguity.

### 4. Why do recurring denials persist?

**Evidence — Reported — B3/B7:** Nia identified recurring denial categories and the monthly ClearBridge report exists, but the case states that nobody has linked denial data upstream.

**Status:** Root-cause linkage is incomplete.

**Resolution plan:** Trace recurring denial categories backward to their originating workflows.

### 5. How much prior-authorization work is chasing versus judgment?

**Evidence — Reported — B3:** Dorothy would hand chasing to an assistant but retain judgment.

**Evidence — Measured — B4:** Shadowing showed payer chasing and clinic-information exceptions.

**Status:** Directionally clear, quantitatively unresolved.

**Resolution plan:** Sample work and classify time by activity and judgment requirement.

### 6. Does the prior-authorization tracker contain unique institutional knowledge?

**Evidence — Measured — B7:** The tracker contained 431 rows.

**Evidence — Reported — B7:** Free-text notes represent approximately 12 years of rules and workarounds.

**Status:** Concentration is evident; portability is untested.

**Resolution plan:** Sample notes and compare them with current payer documentation.

### 7. How much referral workload is caused by fax versus referral complexity?

**Evidence — Measured — B9:** 62% of referrals arrive by fax.

**Evidence — Measured — B4:** Observed processing times varied between clean and problematic documents.

**Status:** Causal contribution is unknown.

**Resolution plan:** Compare processing time and exception rates by intake channel and document quality.

### 8. What prevents safe AI scaling?

**Evidence — Reported — B2/B6:** There is no administrative AI policy and no BAA with a general-purpose AI vendor.

**Evidence — Reported — B6:** Compliance requires defined data flow, accountable ownership, minimum-necessary data, auditability and human review for patient- or claim-affecting outputs.

**Status:** Governance constraints are known; ownership/path are unclear.

**Resolution plan:** Define owner, data classification, review path and vendor requirements for any candidate pilot.

### 9. Is administrative workforce growth caused by volume, inefficiency or organizational design?

**Evidence — Reported — B1:** Kestrel added 63 administrative employees versus 11 clinicians over two years.

**Evidence — Reported — B1:** Patient volume increased 5%.

**Status:** Causal attribution is unknown.

**Resolution plan:** Compare staffing, workload volumes and process changes before attributing growth to automation opportunity.

### 10. Can an opportunity proceed without a new system dependency?

**Evidence — Reported — B3:** Tanya wants work to take less time rather than simply adding another tool.

**Evidence — Reported — B6:** Ken identified APIs, contractual restrictions, payer portals without APIs, spreadsheets, fax and uncertain Access databases.

**Status:** Feasibility varies by workflow.

**Resolution plan:** Map required systems/data flows and assess existing capabilities before proposing new technology.

## Discovery rule

These questions remain visible until evidence resolves them. Where evidence remains unavailable, the final recommendation will state the limitation rather than convert an assumption into a baseline.

**Sources:** B1–B9.
