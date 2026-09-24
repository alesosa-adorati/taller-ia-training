# Kestrel Health Group — Discovery Vocabulary

This vocabulary defines the healthcare, revenue-cycle, operational, and technology terms used throughout the discovery engagement.

| Term                        | Plain-language definition                                                               | Discovery relevance                                              | Source     |
| --------------------------- | --------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Net patient revenue         | Revenue generated from patient care after applicable adjustments                        | Provides the business context for the discovery                  | B1         |
| Cost to collect             | The cost associated with collecting patient and payer revenue                           | Primary executive priority for the discovery                     | B1         |
| Days in A/R                 | Average number of days revenue remains in accounts receivable                           | Indicates collection-cycle performance                           | B1         |
| First-pass claim acceptance | Percentage of claims accepted without being rejected on the first submission            | Indicates upstream claim quality                                 | B1         |
| Prior authorization (PA)    | Approval required from a payer before certain services are provided                     | Major Practice Operations workflow and potential source of delay | B3, B4, B9 |
| Payer                       | Insurance organization responsible for paying eligible claims                           | Determines authorization, billing, enrollment, and payment rules | B3         |
| Clearinghouse               | Service that exchanges and processes claims between providers and payers                | ClearBridge is part of Kestrel's claims-processing environment   | B1, B6     |
| Denial                      | A claim or payment request rejected by a payer                                          | Creates downstream Revenue Cycle work                            | B3, B9     |
| Appeal                      | Formal request asking a payer to reconsider a denial                                    | Requires documentation, policy research, and submission          | B3         |
| PHI                         | Protected Health Information                                                            | Determines data-handling and AI governance requirements          | B6         |
| BAA                         | Business Associate Agreement governing certain relationships involving PHI              | Required for applicable vendors handling PHI                     | B6         |
| Credentialing               | Process of establishing a provider's qualifications with payers and other organizations | Important People/Talent and revenue-enablement workflow          | B3         |
| Payer enrollment            | Registering a provider with an individual payer                                         | Delays can prevent billable care                                 | B3         |
| CPT                         | Standardized procedure code used to identify medical services                           | Appears in prior-authorization and billing workflows             | B4         |
| A/R                         | Accounts receivable; money owed to the organization                                     | Important Revenue Cycle and executive performance metric         | B1         |

## Vocabulary notes

### Revenue Cycle

Revenue Cycle refers to the administrative activities associated with obtaining and collecting payment for healthcare services.

In this discovery, Revenue Cycle includes activities such as claims submission, denial handling, appeals, and related upstream processes.

### Prior Authorization

Prior authorization is a payer approval process that may need to occur before a service is provided.

The case shows that the workflow includes both straightforward requests and requests requiring additional information, payer follow-up, and repeated chasing.

### Denial and Appeal

A denial occurs when a payer rejects a claim or payment request.

An appeal is a subsequent request for the payer to reconsider that decision. The Kestrel case identifies recurring denial categories including missing or invalid prior authorization, eligibility, coding specificity, and medical necessity.

### PHI and AI

PHI is especially important for evaluating AI opportunities.

Kestrel's compliance evidence states that an AI tool handling PHI requires an appropriate BAA and risk assessment. Therefore, technical feasibility alone will not determine whether an AI opportunity can proceed.

### Credentialing and Payer Enrollment

Credentialing and payer enrollment are related but distinct concepts.

Credentialing establishes that a provider meets the relevant qualifications and requirements. Payer enrollment establishes the provider's relationship with an individual payer so that services can be billed appropriately.

## Terms that require careful use

Some terms in the case should not be treated as interchangeable:

* **Prior authorization** is not the same as **claim attachment**.
* **Denials worked** is not the same as **total denials**.
* **AI experimentation** is not the same as **sanctioned AI adoption**.
* **Reported workload estimates** are not the same as **measured system baselines**.
* **Credentialing** is not identical to **payer enrollment**.
* **Technical API availability** does not imply that a system write operation is contractually permitted.

These distinctions will be preserved throughout the discovery to avoid overstat
