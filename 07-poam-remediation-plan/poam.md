# Plan of Action and Milestones

## Purpose

This Plan of Action and Milestones documents the findings, weaknesses, remediation actions, owners, due dates, and validation methods for the BayouTrust Digital Bank GRC assessment.

The purpose of this POA&M is to demonstrate how control gaps are formally tracked from discovery through remediation and validation.

## POA&M Status Definitions

| Status | Definition |
|---|---|
| Open | Remediation has not started or is not yet complete. |
| In Progress | Remediation activities are actively underway. |
| Completed | Remediation has been completed but not yet validated. |
| Validated | Remediation has been reviewed and confirmed effective. |
| Risk Accepted | Management has approved acceptance of the remaining risk. |
| Delayed | Remediation is past the target date. |

## POA&M Tracker

| POA&M ID | Finding ID | Weakness Description | Related Framework | Risk Rating | Remediation Action | Owner | Target Date | Status | Validation Method |
|---|---|---|---|---|---|---|---|---|---|
| POAM-001 | F-001 | Some privileged accounts are not protected by multi-factor authentication. | NIST IA-2, CIS 6, SOC 2 CC6, PCI DSS Req. 8 | High | Enforce MFA for all privileged accounts and document approved exceptions. | IAM Manager | Day 30 | Open | Review privileged account list and MFA enrollment report. |
| POAM-002 | F-002 | Critical vulnerabilities are not always remediated within required timelines. | NIST SI-2, CIS 7, SOC 2 CC7, PCI DSS Req. 6 | High | Create escalation process for overdue critical vulnerabilities and track remediation through tickets. | Infrastructure Manager | Day 30 | Open | Review vulnerability tickets, scan reports, and SLA tracking evidence. |
| POAM-003 | F-003 | Logging coverage does not include all critical systems. | NIST AU-2, AU-6, SI-4, CIS 8, SOC 2 CC7, PCI DSS Req. 10 | High | Add missing critical systems to SIEM log collection and update the log source inventory. | Security Operations Manager | Day 60 | Open | Review SIEM log source inventory and dashboard evidence. |
| POAM-004 | F-004 | PCI segmentation evidence is incomplete. | NIST SC-7, CIS 12, CIS 13, PCI DSS Req. 1 | High | Perform PCI segmentation validation and retain network diagrams, firewall rules, and test evidence. | Network Security Manager | Day 90 | Open | Review segmentation testing results and firewall rule evidence. |
| POAM-005 | F-005 | Backup restoration testing is not consistently documented. | NIST CP-4, CP-9, CIS 11, SOC 2 A1, PCI DSS Req. 12 | High | Perform formal backup restoration testing and retain test results. | Infrastructure Manager | Day 90 | Open | Review restoration test records, screenshots, and recovery validation evidence. |
| POAM-006 | F-006 | Vendor access reviews are not consistently documented. | NIST SR-3, SR-5, CIS 15, SOC 2 CC9, PCI DSS Req. 12 | Medium | Establish quarterly vendor access reviews and document system owner approval. | Vendor Risk Manager | Day 60 | Open | Review vendor access review report and approval evidence. |
| POAM-007 | F-007 | Incident response tabletop testing has not been completed in the last 12 months. | NIST IR-3, IR-4, IR-8, CIS 17, SOC 2 CC7, PCI DSS Req. 12 | Medium | Conduct an incident response tabletop exercise and document lessons learned. | Security Operations Manager | Day 75 | Open | Review tabletop report, attendance records, and lessons learned. |
| POAM-008 | F-008 | User access reviews do not always include complete approval evidence. | NIST AC-2, AC-3, CIS 5, SOC 2 CC6, PCI DSS Req. 7 | Medium | Standardize access review templates and require manager and system owner approval. | GRC Manager | Day 45 | Open | Review completed access review evidence and approval records. |
| POAM-009 | F-009 | Asset inventory may not include all cloud assets. | NIST CM-8, CIS 1, CIS 2, SOC 2 CC5 | Medium | Reconcile asset inventory with cloud resources and update asset ownership records. | Cloud Security Manager | Day 90 | Open | Review updated asset inventory and cloud export. |
| POAM-010 | F-010 | Data classification practices are inconsistent across business units. | NIST SC-8, SC-13, CIS 3, SOC 2 CC6, PCI DSS Req. 3 | Medium | Publish a data classification standard and communicate handling requirements. | GRC Manager | Day 90 | Open | Review approved standard and communication evidence. |

## POA&M Review Process

The POA&M should be reviewed by management on a recurring basis.

Recommended review cadence:

- High-risk items: Monthly
- Medium-risk items: Monthly or quarterly
- Delayed items: Escalated to leadership
- Completed items: Validated before closure

## Closure Criteria

A POA&M item should not be closed until:

- The remediation action is complete.
- Supporting evidence has been collected.
- The control owner confirms completion.
- The GRC team validates the evidence.
- Residual risk is reviewed.
- Management accepts closure or accepts remaining risk.

## Required Evidence for Closure

Evidence may include:

- Screenshots
- System reports
- Access review approvals
- MFA enrollment reports
- Vulnerability scan results
- Ticket records
- Firewall rule exports
- SIEM screenshots
- Tabletop exercise reports
- Backup restoration test results
- Management approvals

## Management Oversight

Management should review POA&M progress to confirm that:

- Owners are assigned.
- Target dates are reasonable.
- High-risk items are prioritized.
- Delayed items are escalated.
- Evidence is retained.
- Residual risk is understood.
- Remediation progress is reported to leadership.

## Summary

The POA&M provides a structured method for tracking cybersecurity and compliance weaknesses through remediation.

This document demonstrates how GRC findings can be translated into assigned actions, timelines, validation steps, and executive accountability.
