# FundPadi | Enterprise IT Risk Assessment

**IT Risk Assessment | IT General Controls (ITGC) | Third-Party Risk | Financial Risk Analysis**

## 1. Executive Project Summary

Conducted a structured enterprise IT risk assessment for **FundPadi Digital Financial Services Ltd**, a fictional Nigerian fintech organisation, as part of a professional GRC training programme.

The assessment examined three critical technology assets: the customer database, mobile application and third-party cloud infrastructure provided by Cloudy Solutions Ltd.

**Key outcomes:**
- Identified and assessed **four technology risks: three High and one Medium**.
- Evaluated access management, customer authentication, service availability and third-party data security.
- Calculated **₦43 million in combined illustrative annual loss expectancy (ALE)** across three risk scenarios.
- Developed risk treatment recommendations, conditional residual risk estimates, Key Risk Indicators (KRIs) and management remediation priorities.

The project demonstrates a risk-based approach to identifying control weaknesses, evaluating potential business impact and communicating actionable recommendations to management.

## 2. Risk Assessment Results

A 5 × 5 likelihood-impact matrix was used to evaluate the four scenarios.

| Risk ID | Risk Scenario | Likelihood | Impact | Initial Score | Rating |
|---|---|---:|---:|---:|---|
| R01 | Unauthorised administrator access to customer database | 4 | 4 | 16 | High |
| R02 | Unauthorised customer account access and transfers | 4 | 4 | 16 | High |
| R03 | Cloud service disruption | 3 | 3 | 9 | Medium |
| R04 | Potential customer data compromise through cloud provider | 3 | 4 | 12 | High |

The assessment prioritised R01, R02 and R04 as High-rated risks while retaining R03 for treatment because service availability remains important to customer operations.

## 3. Assessment Methodology and Evidence Limitations

The assessment followed a structured risk evaluation process:

1. Identified critical technology assets, threats and relevant control weaknesses.
2. Distinguished **confirmed weaknesses from missing documentation and unverified incidents**.
3. Assessed likelihood and business impact using a 5 × 5 risk matrix.
4. Selected mitigation strategies and recommended proportionate security controls.
5. Modelled potential financial exposure using Single Loss Expectancy (SLE), Annual Rate of Occurrence (ARO) and Annual Loss Expectancy (ALE).
6. Proposed conditional residual risk ratings, KRIs, accountable owners and remediation milestones.

**Evidence-based judgement:** The absence of documented login rate limiting or supplier reviews was treated as an evidence gap, not proof that the controls were absent. Increased complaints about unauthorised transfers were treated as warning signs requiring investigation, not confirmation of fraud.

## 4. Key Findings and Recommended Controls

| Risk | Principal Concern | Recommended Response |
|---|---|---|
| **R01 — Database access** | Missing administrator MFA, shared privileged credentials and unusual logins | Enforce administrator MFA, individual accounts, least-privilege access, privileged access management and automated monitoring |
| **R02 — Mobile security** | Missing customer MFA and increasing complaints about unauthorised transfers | Introduce customer MFA, verify login rate limiting, strengthen transaction verification and investigate complaints |
| **R03 — Cloud availability** | Previous three-hour outage affecting one customer-facing service | Investigate the outage, strengthen service-level agreements, define recovery objectives and test restoration procedures |
| **R04 — Cloud data security** | Insufficient documented supplier assurance and unclear contractual responsibilities | Conduct vendor security due diligence, clarify data protection responsibilities and verify security controls |

A key analytical decision was to assess **cloud availability (R03) separately from cloud data security (R04)**, as they involve different events, consequences and control responses.

## 5. Financial Risk Analysis

The assessment applied the formula:

**Annual Loss Expectancy (ALE) = Single Loss Expectancy (SLE) × Annual Rate of Occurrence (ARO)**

| Risk | SLE — Estimated Loss per Incident | ARO | Modelled Annual Loss |
|---|---:|---:|---:|
| R01 — Customer database | ₦30,000,000 | 0.5 | ₦15,000,000 |
| R02 — Mobile application | ₦12,000,000 | 1.5 | ₦18,000,000 |
| R03 — Cloud disruption | ₦5,000,000 | 2.0 | ₦10,000,000 |
| **Total** | | | **₦43,000,000** |

R02 had the highest modelled annual exposure, while R01 had the highest estimated loss from a single incident.

**Limitations:** The calculations use illustrative case-study assumptions, not verified incident frequencies or actual recorded losses. R04 was not quantified because sufficient financial inputs were unavailable. Therefore, ₦43 million is not a complete estimate of all four risks.

## 6. Skills Demonstrated

| Competency | Evidence from Project |
|---|---|
| **IT risk assessment** | Developed risk scenarios and assigned likelihood-impact ratings |
| **ITGC and access management** | Evaluated administrator access, authentication, privileged permissions and monitoring weaknesses |
| **Third-party technology risk** | Separately assessed cloud availability and supplier data security |
| **Financial risk analysis** | Calculated SLE, ARO and ALE for three scenarios |
| **Control evaluation and recommendations** | Linked identified weaknesses to proposed preventive, detective and recovery controls |
| **Risk reporting** | Produced a management report, risk workbook and executive presentation |
| **Risk monitoring and remediation** | Proposed KRIs, conditional residual ratings, control owners and remediation priorities |

## 7. Project Deliverables

The completed assessment includes:

- 📊 [Enterprise Risk Assessment Workbook](FundPadi_Enterprise_Risk_Assessment_Workbook.xlsx) — Risk assessment and supporting analysis.
- 📄 [Management Risk Assessment Report](FundPadi_Management_Report.docx) — Detailed findings, risk evaluation, recommended controls and management actions.
- 📽️ [Management Risk Presentation](FundPadi_Management_Risk_Presentation.pptx) — Executive briefing summarising risk exposure, priorities and decisions.

## 8. Disclaimer

This is an **educational case study involving a fictional organisation**, not a live client audit.

Risk ratings, financial estimates and recommendations are based on the supplied scenario and stated assumptions. Proposed residual risk ratings are conditional on successful implementation and verification of the recommended controls.

The project demonstrates IT risk assessment and control evaluation skills; it does not claim independently verified operating effectiveness of controls in a live environment.
