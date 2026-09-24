# Kestrel Health Group — Client Brief

## 1. What Kestrel does and how it makes money

Kestrel Health Group is a multi-specialty physician group operating outpatient medical services in North Carolina. Its clinical footprint includes primary care, orthopedics, cardiology, endocrinology, and imaging.

The discovery is focused on four administrative departments:

- Revenue Cycle
- Practice Operations
- People / Talent
- Patient Growth

**Measured — B1:** The in-scope population is 473 administrative employees across these four departments.

**Measured — B1:** Kestrel has 218 clinicians and 31 outpatient sites.

**Reported — B1:** Net patient revenue is $412M, with revenue growing 7% and patient volume growing 5%.

The business concern is not simply administrative workload. Leadership is focused on the cost of collecting revenue and on whether administrative work is growing faster than clinical capacity.

**Measured — B1:** Cost to collect is 4.1%, compared with a reported peer median of approximately 3.2%.

**Measured — B1:** Days in A/R increased from 41 to 46.

**Measured — B1:** First-pass claim acceptance is below 88%.

**Reported — B1:** Kestrel added 63 administrative employees versus 11 clinicians over the previous two years.

The COO, Marcus Bell, has explicitly asked the discovery team to understand what the approximately 470 administrative employees do and how much of that work should be performed by a person.

His stated priority is cost to collect. He has also explicitly said that the conclusion could be that Kestrel should hire fewer people and buy no new technology.

**Source:** B1 Company.

## 2. Kestrel's relationship with AI

Kestrel has already experimented with AI, but adoption and governance are inconsistent.

**Reported — B1/B2:** In 2024, Kestrel ran an AI ambient-scribe pilot with 40 clinicians. Twelve clinicians still used it daily, while 28 stopped within six weeks. No baseline was measured for the pilot.

**Measured — B2 survey:** 51% of survey respondents who answered the AI-use question reported using AI for work.

**Measured — B2 survey:** Among those AI users, 71% reported using a personal, non-Kestrel account.

**Measured — B2 survey:** Only 6% of respondents reported receiving AI training.

No AI tools are formally sanctioned for administrative staff according to the COO's current understanding, although the case also identifies four Copilot licenses in the Patient Growth team.

**Reported — B2:** Among employees who use AI for work, 9% reported daily use, 19% weekly use, and 72% occasional or rare use.

The most common reported uses are:

- Writing/editing
- Summarization
- Information lookup
- Spreadsheet formulas

The survey also shows that employees are already experimenting with AI despite the absence of a clear administrative AI policy.

**Measured — B2 survey:** 38% of respondents identified uncertainty about whether AI use is allowed as a concern.

**Measured — B2 survey:** 27% identified privacy as a concern and 18% identified accuracy as a concern.

One employee reported that AI hallucinated a nonexistent policy when used for an appeal.

The 2024 clinical scribe pilot had a BAA, but Kestrel currently has no BAA with a general-purpose AI vendor.

**Reported — B6:** Any AI tool handling PHI requires a signed BAA and risk assessment. Sandra estimates a minimum of 6–8 weeks for this process, potentially longer for an inexperienced healthcare vendor.

This means AI capability exists at the employee level, but controlled organizational adoption is immature.

**Sources:** B1, B2, B6, B8.

## 3. Working vocabulary

The discovery will use healthcare, revenue-cycle, and operational terminology that may not be familiar to a general technology audience.

| Term | Plain-language meaning | Why it matters |
|---|---|---|
| Net patient revenue | Revenue generated from patient care after applicable adjustments | Core business outcome |
| Cost to collect | Administrative cost associated with collecting patient and payer revenue | Primary COO priority |
| Days in A/R | Average number of days revenue remains in accounts receivable | Indicates collection-cycle performance |
| First-pass claim acceptance | Percentage of claims accepted without being rejected on the first submission | Indicates upstream claim quality |
| Prior authorization (PA) | Approval required from a payer before certain services are provided | Major Practice Operations workload |
| Payer | Insurance organization responsible for paying eligible claims | Determines authorization, billing, and enrollment rules |
| Clearinghouse | Service that exchanges and processes claims between providers and payers | ClearBridge is Kestrel's claims clearinghouse |
| Denial | A claim or payment request rejected by a payer | Creates downstream revenue-cycle work |
| Appeal | Formal request asking a payer to reconsider a denial | Requires documentation, policy research, and submission |
| PHI | Protected Health Information | Determines data-handling and AI requirements |
| BAA | Business Associate Agreement governing certain PHI handling relationships | Required for applicable vendors handling PHI |
| Credentialing | Process of establishing a provider's qualifications with payers and other organizations | Required before providers can bill certain payers |
| Payer enrollment | Registering a provider with an individual payer | Delays can prevent billable care |
| CPT | Standardized procedure coding used for medical services | Appears in prior-authorization and billing workflows |
| A/R | Accounts receivable; money owed to the organization | Key revenue-cycle metric |

**Sources:** B1, B3, B6, B9.

## 4. Key people and roles

### Marcus Bell — COO

Executive sponsor for the discovery.

His stated priority is reducing cost to collect and understanding what administrative employees do. He has explicitly asked the team not to assume that the answer requires new technology.

**Reported quote — B1:** “Finding the money is not my problem. Finding the person who will own this on my side is my problem.”

This creates an important discovery constraint: recommendations must identify an operational owner, not only a technical solution.

### Sandra Whitlock — CCO

Key governance and compliance stakeholder.

She is responsible for understanding data handling, PHI requirements, BAAs, risk assessments, auditability, minimum-necessary data, and human review requirements.

### Ken — IT

Provides system and integration information.

Important findings include a documented Caregate read API, a restricted Caregate write capability, a ClearBridge API, RightFax API access, and uncertainty around some Access databases.

### Tanya Brooks — VP Revenue Cycle

Owns the Revenue Cycle organization and is measured on cost to collect and A/R.

**Reported quote — B3:** “I don't need a tool. I need the same work to take less time.”

### Hector Salinas — Director, Practice Operations

Owns referral intake, prior authorization, scheduling, and records.

He identified prior authorization as a persistent operational concern and explicitly identified dependency on Dorothy.

### Dorothy Kimball — Prior Authorization Coordinator

Experienced operational subject-matter expert with 19 years at Kestrel.

She maintains a long-lived prior-authorization tracker and is the primary source of practical knowledge about payer-specific workarounds.

She distinguishes between administrative chasing work and clinical judgment, indicating a potentially important boundary for any future AI-assisted workflow.

### Nia Croft — Billing Specialist

Works denials and appeals.

She identified recurring upstream problems involving prior authorization, eligibility, coding specificity, and medical necessity.

### Aaron Petit — Referral Intake

Works inbound referrals.

He identified fax processing and manual data entry as significant workload components.

### Marisol Vega — Credentialing Lead

Leads credentialing work and maintains the operational knowledge around payer-specific enrollment requirements.

### Wendy Ofori — People Operations

Raises important questions around handling sensitive credentialing information, including regulated identifiers and professional history.

### Ellis Chang — Marketing

Uses Copilot for recurring practice-growth reporting and provides evidence that controlled AI usage already exists in at least one administrative team.

**Sources:** B1, B3, B6, B8.

## 5. Available documentation and evidence

Kestrel has several existing sources of operational information:

- **Measured/system artifact — B7:** Prior-authorization tracker containing 431 rows at observation and 14 columns.
- **Measured/system artifact — B7:** Referral fax lookup spreadsheet containing approximately 900 rows.
- **Measured/system artifact — B7:** Appeal folder containing approximately 1,400 documents.
- **Measured/system artifact — B7:** Credentialing tracker shared by four specialists.
- **Measured/system artifact — B7:** ClearBridge denial-reason report available monthly.
- **Reported — B1:** An 84-page Revenue Cycle manual from 2021.
- **Reported — B1:** Front-desk onboarding material from 2023.
- **Reported — B1:** Organization charts and systems inventory.

Important documentation gaps exist.

Kestrel does not have identified prior-authorization or referral procedures covering the relevant work in sufficient detail, and there is no administrative AI policy.

The operational spreadsheets contain knowledge that is not fully represented in core systems. The prior-authorization tracker includes free-text notes representing approximately 12 years of rules and workarounds.

**Sources:** B1, B6, B7.

## 6. Initial discovery posture

The discovery should not begin with a predetermined AI solution.

The available evidence suggests several potentially important themes:

1. Administrative work is distributed across core systems, portals, spreadsheets, fax queues, and individual knowledge.
2. Several workflows contain repetitive information handling combined with human judgment.
3. Some operational knowledge is concentrated in individual employees or locally maintained artifacts.
4. AI experimentation already exists, but organizational governance and sanctioned usage are immature.
5. The primary business question is economic and operational: whether the same work can be completed with less cost and less avoidable effort.
6. Any PHI-bearing AI workflow will face governance and implementation constraints before technical feasibility becomes the only consideration.

These are discovery hypotheses, not final recommendations.

**Sources:** B1–B9.