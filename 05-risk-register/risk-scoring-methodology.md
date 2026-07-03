# Risk Scoring Methodology

## Purpose

This document defines the risk scoring methodology used in the BayouTrust Digital Bank GRC assessment.

The purpose of this methodology is to provide a consistent way to evaluate, compare, and prioritize cybersecurity and compliance risks.

## Risk Formula

Risk is calculated using likelihood and impact.

**Risk Score = Likelihood x Impact**

| Risk Score | Risk Rating |
|---|---|
| 1-5 | Low |
| 6-10 | Medium |
| 11-15 | High |
| 16-25 | Critical |

## Likelihood Scale

Likelihood measures how probable it is that a risk event may occur.

| Score | Likelihood | Description |
|---:|---|---|
| 1 | Rare | The event is unlikely to occur. |
| 2 | Unlikely | The event could occur but is not expected. |
| 3 | Possible | The event may occur under certain conditions. |
| 4 | Likely | The event is expected to occur. |
| 5 | Almost Certain | The event is expected to occur frequently or repeatedly. |

## Impact Scale

Impact measures the potential business, security, compliance, financial, operational, or reputational effect if the risk occurs.

| Score | Impact | Description |
|---:|---|---|
| 1 | Minimal | Limited impact with little disruption. |
| 2 | Minor | Some impact that can be handled through normal operations. |
| 3 | Moderate | Noticeable impact requiring management attention. |
| 4 | Major | Significant impact to business, compliance, security, or operations. |
| 5 | Severe | Major financial, legal, regulatory, operational, or reputational impact. |

## Risk Rating Definitions

| Rating | Definition | Management Action |
|---|---|---|
| Low | Limited risk exposure. | Monitor through normal operations. |
| Medium | Moderate risk exposure. | Assign owner and remediate through normal governance. |
| High | Significant risk exposure. | Prioritize remediation and report to management. |
| Critical | Severe risk exposure. | Immediate leadership attention and urgent remediation required. |

## Risk Categories

Risks may be grouped into the following categories:

- Identity and Access Management
- Vulnerability Management
- Logging and Monitoring
- Incident Response
- Vendor Risk Management
- Data Protection
- Business Continuity
- PCI Readiness
- SOC 2 Readiness
- Cloud Security
- Governance
- Audit Readiness

## Risk Treatment Options

| Treatment | Description |
|---|---|
| Mitigate | Take action to reduce likelihood or impact. |
| Accept | Management formally accepts the risk. |
| Transfer | Shift part of the risk through insurance, contracts, or third parties. |
| Avoid | Stop the activity that creates the risk. |

## Example Risk Scoring

| Risk Statement | Likelihood | Impact | Score | Rating |
|---|---:|---:|---:|---|
| Privileged accounts may not be protected by MFA. | 4 | 5 | 20 | Critical |
| Vendor access reviews may be incomplete. | 3 | 4 | 12 | High |
| Data classification practices may be inconsistent. | 3 | 4 | 12 | High |
| Security awareness evidence may be incomplete. | 2 | 3 | 6 | Medium |

## Residual Risk

Residual risk is the risk that remains after remediation or compensating controls are applied.

Residual risk should be reviewed when:

- A remediation action is completed.
- A risk is accepted.
- A compensating control is implemented.
- A major business or technology change occurs.

## Risk Review Cadence

Recommended review cadence:

| Risk Rating | Review Frequency |
|---|---|
| Critical | Monthly |
| High | Monthly |
| Medium | Quarterly |
| Low | Semi-annually or annually |

## Summary

A consistent risk scoring methodology helps leadership understand which risks require immediate action and which risks can be managed through normal governance processes.

This methodology supports the risk register, gap analysis, POA&M, executive reporting, and audit readiness activities.
