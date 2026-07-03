# Risk Register Template

## Purpose

This template can be used to document, score, prioritize, and track cybersecurity, compliance, operational, and third-party risks.

A risk register helps the organization maintain visibility into known risks, assign risk owners, document treatment plans, and monitor remediation progress.

## Risk Scoring Methodology

Risk is scored using likelihood and impact.

**Risk Score = Likelihood x Impact**

| Score Range | Risk Rating |
|---|---|
| 1-5 | Low |
| 6-10 | Medium |
| 11-15 | High |
| 16-25 | Critical |

## Likelihood Scale

| Score | Likelihood | Description |
|---|---|---|
| 1 | Rare | The risk is unlikely to occur. |
| 2 | Unlikely | The risk could occur, but is not expected. |
| 3 | Possible | The risk may occur under certain conditions. |
| 4 | Likely | The risk is expected to occur. |
| 5 | Almost Certain | The risk is expected to occur frequently or repeatedly. |

## Impact Scale

| Score | Impact | Description |
|---|---|---|
| 1 | Minimal | Limited business, security, or compliance impact. |
| 2 | Minor | Some impact to operations, security, or compliance. |
| 3 | Moderate | Noticeable impact requiring management attention. |
| 4 | Major | Significant business, security, compliance, or operational impact. |
| 5 | Severe | Major financial, legal, regulatory, operational, or reputational impact. |

## Risk Treatment Options

| Treatment | Description |
|---|---|
| Mitigate | Take action to reduce the likelihood or impact of the risk. |
| Accept | Accept the risk with management approval. |
| Transfer | Shift part of the risk through insurance, contract terms, or third-party agreements. |
| Avoid | Stop the activity or process that creates the risk. |

## Risk Register

| Risk ID | Risk Statement | Category | Likelihood | Impact | Risk Score | Rating | Risk Owner | Treatment | Remediation Action | Target Date | Status |
|---|---|---|---:|---:|---:|---|---|---|---|---|---|
| R-001 | Example: Privileged accounts may not be protected by MFA. | Identity and Access Management | 4 | 5 | 20 | Critical | IAM Manager | Mitigate | Enforce MFA for all privileged accounts. | TBD | Open |
| R-002 | Example: Critical vulnerabilities may not be remediated within SLA. | Vulnerability Management | 4 | 4 | 16 | Critical | Infrastructure Manager | Mitigate | Create escalation process for overdue vulnerabilities. | TBD | Open |
| R-003 | Example: Vendor access may not be reviewed regularly. | Vendor Risk Management | 3 | 4 | 12 | High | Vendor Risk Manager | Mitigate | Establish quarterly vendor access reviews. | TBD | Open |

## Risk Review Cadence

Risks should be reviewed on a regular basis.

Recommended review frequency:

- Critical risks: Monthly
- High risks: Monthly or quarterly
- Medium risks: Quarterly
- Low risks: Semi-annually or annually

## Required Fields

Each risk should include:

- Risk ID
- Risk statement
- Risk category
- Likelihood score
- Impact score
- Overall risk rating
- Risk owner
- Treatment decision
- Remediation action
- Target date
- Status

## Summary

This template helps standardize how risks are documented, scored, assigned, and tracked through remediation.
