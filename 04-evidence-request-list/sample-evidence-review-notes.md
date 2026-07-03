# Sample Evidence Review Notes

## Purpose

This document provides sample evidence review notes for the BayouTrust Digital Bank GRC assessment.

The purpose is to demonstrate how audit or assessment evidence can be reviewed, documented, and connected to control conclusions.

## Evidence Review Criteria

Evidence is reviewed based on the following criteria:

| Criteria | Description |
|---|---|
| Relevance | Evidence supports the specific control being tested. |
| Completeness | Evidence includes all required information. |
| Timeliness | Evidence is current for the assessment period. |
| Accuracy | Evidence appears reliable and consistent with the control objective. |
| Approval | Evidence includes required approvals or sign-offs when applicable. |
| Traceability | Evidence can be linked to the system, process, or control being tested. |

## Evidence Review Notes

| Evidence ID | Related Control | Evidence Reviewed | Review Result | Notes | Follow-Up Required |
|---|---|---|---|---|---|
| EV-001 | IAM-001 | MFA policy and remote access configuration screenshot. | Sufficient | Evidence supports MFA enforcement for standard remote access users. | No |
| EV-002 | IAM-002 | Privileged account list and MFA enrollment report. | Insufficient | Some privileged accounts are not shown as enrolled in MFA. | Yes |
| EV-003 | IAM-003 | Quarterly access review report. | Partially Sufficient | Access review was performed, but some manager approvals are missing. | Yes |
| EV-004 | VM-001 | Internal and external vulnerability scan reports. | Sufficient | Scan reports were current and covered major system groups. | No |
| EV-005 | VM-002 | Vulnerability remediation ticket export. | Partially Sufficient | Several critical vulnerabilities exceeded the required remediation timeframe. | Yes |
| EV-006 | LOG-001 | SIEM dashboard and log source inventory. | Insufficient | Log source inventory does not include all critical systems. | Yes |
| EV-007 | IR-001 | Incident response plan and escalation matrix. | Sufficient | Current IR plan was provided. | No |
| EV-008 | IR-002 | Tabletop exercise evidence. | Not Provided | No recent tabletop report or lessons learned document was provided. | Yes |
| EV-009 | VRM-001 | Vendor due diligence checklist and vendor questionnaire. | Sufficient | Evidence supports vendor onboarding review. | No |
| EV-010 | VRM-002 | Vendor access list. | Insufficient | Vendor access review approval evidence was not provided. | Yes |
| EV-011 | DP-001 | Encryption standard and cloud encryption screenshots. | Sufficient | Evidence supports encryption for sensitive data. | No |
| EV-012 | BC-002 | Backup restoration test evidence. | Insufficient | Backup job reports were provided, but restoration testing evidence was incomplete. | Yes |
| EV-013 | PCI-001 | Network diagram and firewall rule request. | Insufficient | Segmentation testing evidence was missing. | Yes |

## Follow-Up Items

The following evidence items require follow-up:

1. Privileged account MFA enrollment evidence
2. Access review approval evidence
3. Critical vulnerability SLA evidence
4. SIEM log source inventory update
5. Incident response tabletop exercise evidence
6. Vendor access review approval evidence
7. Backup restoration testing evidence
8. PCI segmentation testing evidence

## Evidence Review Conclusion

The evidence review identified several controls with sufficient evidence, but also several areas where documentation was incomplete.

The strongest evidence was related to:

- Standard remote access MFA
- Vulnerability scan completion
- Incident response plan documentation
- Vendor onboarding due diligence
- Encryption controls

The weakest evidence was related to:

- Privileged account MFA
- Access review approvals
- Logging coverage
- Incident response testing
- Vendor access reviews
- Backup restoration testing
- PCI segmentation validation

## Summary

Evidence quality is a key part of audit readiness.

Even when a control exists, missing or incomplete evidence can result in findings, remediation actions, or audit exceptions.
