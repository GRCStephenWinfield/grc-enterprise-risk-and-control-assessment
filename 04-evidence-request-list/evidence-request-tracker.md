# Evidence Request Tracker

## Purpose

This document provides a sample evidence request tracker for the BayouTrust Digital Bank GRC assessment.

The purpose of this tracker is to demonstrate how evidence is requested, tracked, reviewed, and linked to control testing during an audit or GRC assessment.

## Evidence Review Status Definitions

| Status | Definition |
|---|---|
| Not Requested | Evidence has not yet been requested from the control owner. |
| Requested | Evidence has been requested but not yet received. |
| Received | Evidence has been received but not fully reviewed. |
| Reviewed | Evidence has been reviewed and documented. |
| Insufficient | Evidence was received but does not fully support the control. |
| Overdue | Evidence was not received by the requested due date. |

## Evidence Request Tracker

| Request ID | Control Area | Evidence Requested | Control Owner | Due Date | Status | Review Notes |
|---|---|---|---|---|---|---|
| ER-001 | Identity and Access Management | Current MFA policy and configuration screenshots for remote access users. | IAM Manager | 2026-07-15 | Reviewed | Evidence supports MFA enforcement for standard remote users. |
| ER-002 | Privileged Access Management | List of privileged accounts and MFA enrollment report. | IAM Manager | 2026-07-15 | Insufficient | Report shows some privileged accounts are not enrolled in MFA. |
| ER-003 | User Access Reviews | Most recent quarterly access review reports for critical systems. | Application Owners | 2026-07-18 | Insufficient | Evidence does not include all required manager approvals. |
| ER-004 | Vulnerability Management | Most recent internal and external vulnerability scan reports. | Security Operations Manager | 2026-07-15 | Reviewed | Scan reports were provided and appear complete. |
| ER-005 | Patch Management | Critical vulnerability remediation report and SLA tracking evidence. | Infrastructure Manager | 2026-07-18 | Reviewed | Evidence shows several critical vulnerabilities exceeded SLA. |
| ER-006 | Logging and Monitoring | SIEM log source inventory and alert review records. | Security Operations Manager | 2026-07-20 | Insufficient | Log source inventory does not include all critical systems. |
| ER-007 | Incident Response | Current incident response plan and escalation matrix. | Security Operations Manager | 2026-07-15 | Reviewed | Incident response plan and escalation contacts were provided. |
| ER-008 | Incident Response Testing | Most recent tabletop exercise report and lessons learned. | Security Operations Manager | 2026-07-20 | Overdue | Evidence was not provided by the due date. |
| ER-009 | Vendor Risk Management | Vendor due diligence records for high-risk vendors. | Vendor Risk Manager | 2026-07-22 | Received | Evidence received and pending detailed review. |
| ER-010 | Vendor Access Reviews | Current vendor access list and most recent access review evidence. | Vendor Risk Manager | 2026-07-22 | Insufficient | Vendor access list was provided, but approval evidence is missing. |
| ER-011 | Data Protection | Encryption standard and encryption configuration evidence. | Cloud Security Manager | 2026-07-18 | Reviewed | Encryption evidence supports data protection control expectations. |
| ER-012 | Backup and Recovery | Backup job reports for critical systems. | Infrastructure Manager | 2026-07-19 | Reviewed | Backup jobs are running for critical systems. |
| ER-013 | Backup Restoration Testing | Backup restoration test results and recovery screenshots. | Infrastructure Manager | 2026-07-19 | Insufficient | Restoration testing evidence is incomplete. |
| ER-014 | PCI Segmentation | Network diagram, firewall rules, and segmentation testing evidence. | Network Security Manager | 2026-07-22 | Insufficient | Network diagram was provided, but segmentation testing evidence is missing. |
| ER-015 | Governance | Annual cybersecurity policy review and approval evidence. | GRC Manager | 2026-07-15 | Reviewed | Policy approval records were provided and appear complete. |

## Evidence Summary

| Status | Count |
|---|---:|
| Reviewed | 7 |
| Insufficient | 6 |
| Received | 1 |
| Overdue | 1 |
| Requested | 0 |
| Not Requested | 0 |

## Key Evidence Gaps

The assessment identified the following evidence gaps:

1. Privileged account MFA enrollment evidence is incomplete.
2. Quarterly access review evidence does not include all required approvals.
3. SIEM log source inventory does not include all critical systems.
4. Incident response tabletop testing evidence was not provided.
5. Vendor access review approval evidence is missing.
6. Backup restoration testing evidence is incomplete.
7. PCI segmentation testing evidence is missing.

## Recommended Evidence Improvements

The organization should improve evidence collection by:

- Assigning evidence owners for each control area.
- Using a centralized evidence repository.
- Requiring control owners to submit evidence before audit deadlines.
- Maintaining screenshots, reports, approvals, and system exports.
- Tracking missing evidence through the POA&M.
- Reviewing evidence quality before submitting to auditors.
- Retaining evidence according to record retention requirements.

## Summary

Evidence collection is a critical part of GRC and audit readiness.

This tracker shows how evidence requests can be documented, assigned, reviewed, and linked to control testing results.
