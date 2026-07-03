# Control Assessment Template

## Purpose

This template is used to document cybersecurity and compliance control testing results.

A control assessment helps determine whether a control is properly designed, operating effectively, supported by evidence, and reducing risk as expected.

## Control Rating Definitions

| Rating | Definition |
|---|---|
| Effective | The control is properly designed, operating as expected, and supported by sufficient evidence. |
| Needs Improvement | The control exists, but there are design, operating, documentation, or evidence weaknesses. |
| Ineffective | The control is missing, not operating, or unsupported by evidence. |
| Not Tested | The control was not tested during the assessment period. |

## Evidence Quality Definitions

| Evidence Rating | Definition |
|---|---|
| Sufficient | Evidence fully supports the control requirement. |
| Partially Sufficient | Evidence supports part of the control but has gaps. |
| Insufficient | Evidence does not support the control requirement. |
| Not Provided | Evidence was not received. |

## Control Assessment Tracker

| Control ID | Control Area | Control Description | Framework Mapping | Control Owner | Evidence Reviewed | Design Effectiveness | Operating Effectiveness | Evidence Quality | Final Rating | Risk Rating | Recommendation |
|---|---|---|---|---|---|---|---|---|---|---|---|
| CTRL-001 | Access Control | Example: MFA is required for remote access. | NIST IA-2, CIS 6, SOC 2 CC6, PCI DSS Req. 8 | IAM Manager | MFA report, screenshots, policy | Effective | Effective | Sufficient | Effective | Low | Continue monitoring quarterly. |
| CTRL-002 | Vulnerability Management | Example: Critical vulnerabilities are remediated within SLA. | NIST SI-2, CIS 7, SOC 2 CC7, PCI DSS Req. 6 | Infrastructure Manager | Scan report, tickets, SLA report | Effective | Needs Improvement | Partially Sufficient | Needs Improvement | High | Create escalation process for overdue items. |
| CTRL-003 | Incident Response | Example: Tabletop exercises are performed annually. | NIST IR-4, CIS 17, SOC 2 CC7, PCI DSS Req. 12 | Security Operations Manager | IR plan, tabletop evidence | Needs Improvement | Ineffective | Not Provided | Ineffective | Medium | Conduct and document annual tabletop exercise. |

## Control Testing Procedure

For each control, document:

1. Control objective
2. Framework mapping
3. Control owner
4. Evidence requested
5. Evidence reviewed
6. Design effectiveness
7. Operating effectiveness
8. Evidence quality
9. Final rating
10. Risk rating
11. Recommendation
12. Remediation owner

## Sample Control Narrative

### Control ID

CTRL-001

### Control Objective

Confirm that multi-factor authentication is required for remote access.

### Testing Procedure

Review the MFA policy, identity provider configuration, and MFA enrollment report to determine whether MFA is enabled for remote users.

### Evidence Reviewed

- MFA policy
- Identity provider screenshot
- MFA enrollment report

### Result

Evidence supports that MFA is enabled for standard remote access users.

### Rating

Effective

### Recommendation

Continue monitoring MFA enforcement and review configuration quarterly.

## Summary

This template helps standardize control testing and supports GRC assessments, audit readiness, framework mapping, risk registers, and POA&M tracking.
