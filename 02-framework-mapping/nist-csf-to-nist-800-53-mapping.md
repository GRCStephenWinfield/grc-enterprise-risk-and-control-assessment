# NIST CSF to NIST 800-53 Mapping

## Purpose

This document maps selected NIST Cybersecurity Framework 2.0 outcomes to related NIST SP 800-53 Rev. 5 controls.

The purpose is to demonstrate how high-level cybersecurity outcomes can be connected to detailed security and privacy controls.

## Mapping Overview

NIST CSF provides a high-level structure for cybersecurity risk management. NIST SP 800-53 provides more detailed control requirements that can support implementation, assessment, and evidence collection.

## NIST CSF Functions Used

| NIST CSF Function | Description |
|---|---|
| Govern | Establish cybersecurity risk management strategy, policy, oversight, and accountability. |
| Identify | Understand assets, risks, business context, and dependencies. |
| Protect | Implement safeguards to manage cybersecurity risk. |
| Detect | Identify and analyze possible cybersecurity events. |
| Respond | Take action regarding detected cybersecurity incidents. |
| Recover | Restore assets and operations affected by cybersecurity incidents. |

## NIST CSF to NIST 800-53 Mapping

| Control Area | NIST CSF Function | NIST CSF Category | Related NIST 800-53 Controls | Example Evidence |
|---|---|---|---|---|
| Governance | Govern | GV.OC, GV.RM, GV.OV | PM-1, PM-9, RA-3, CA-2 | Cybersecurity policy, risk register, management review records |
| Risk Assessment | Identify | ID.RA | RA-3, RA-5, PM-9 | Risk assessment report, risk register, vulnerability scan reports |
| Asset Management | Identify | ID.AM | CM-8, PM-5 | Asset inventory, cloud asset export, system ownership records |
| Identity Management | Protect | PR.AA | AC-2, AC-3, IA-2 | User access list, MFA report, access control policy |
| Privileged Access | Protect | PR.AA | AC-2, AC-5, AC-6, IA-2 | Privileged account list, MFA enrollment report, access approvals |
| Awareness and Training | Protect | PR.AT | AT-2, AT-3 | Training completion report, awareness policy |
| Data Security | Protect | PR.DS | SC-8, SC-13, MP-5 | Encryption standard, data classification standard, configuration screenshots |
| Configuration Management | Protect | PR.PS | CM-2, CM-6 | Secure configuration baseline, configuration scan results |
| Vulnerability Management | Identify / Protect | ID.RA, PR.PS | RA-5, SI-2 | Vulnerability scan reports, patch reports, remediation tickets |
| Logging and Monitoring | Detect | DE.CM | AU-2, AU-6, SI-4 | SIEM dashboard, log source inventory, alert review evidence |
| Incident Response | Respond | RS.MA, RS.CO | IR-4, IR-6, IR-8 | Incident response plan, escalation matrix, tabletop exercise report |
| Recovery | Recover | RC.RP, RC.CO | CP-2, CP-4, CP-9 | Backup reports, restoration test results, recovery plan |
| Supply Chain Risk | Govern | GV.SC | SR-3, SR-5, SR-6 | Vendor risk assessment, vendor access review, SOC 2 report |

## Example Control Relationship

Multi-factor authentication is a good example of how one control supports multiple framework areas.

| Item | Example |
|---|---|
| NIST CSF Category | PR.AA |
| NIST 800-53 Controls | IA-2, AC-2, AC-3 |
| Evidence | MFA policy, identity provider screenshots, MFA enrollment report |
| Risk Reduced | Unauthorized access risk |

## Assessment Use

This mapping supports:

- Control assessment
- Evidence request planning
- Risk register development
- Gap analysis
- POA&M tracking
- Audit readiness
- Executive reporting

## Summary

Mapping NIST CSF to NIST 800-53 helps connect high-level cybersecurity outcomes to detailed control requirements.

This allows GRC teams to evaluate whether the organization has enough evidence, ownership, and control activity to support cybersecurity risk management.
