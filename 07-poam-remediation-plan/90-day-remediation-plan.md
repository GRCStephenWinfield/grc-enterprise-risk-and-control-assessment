# 90-Day Remediation Plan

## Purpose

This document provides a 90-day remediation plan for the highest-priority risks and control gaps identified during the BayouTrust Digital Bank GRC assessment.

The purpose of this plan is to demonstrate how findings can be prioritized, assigned, tracked, and remediated through a formal governance process.

## Remediation Priority Definitions

| Priority | Definition |
|---|---|
| High | Remediation should begin immediately due to significant risk or compliance exposure. |
| Medium | Remediation should be planned and completed through normal governance processes. |
| Low | Remediation can be scheduled as part of continuous improvement activities. |

## 90-Day Remediation Roadmap

| Timeframe | Focus Area | Key Actions |
|---|---|---|
| Days 1-30 | High-Risk Access and Vulnerability Items | Enforce MFA for privileged accounts, identify critical vulnerability backlog, assign remediation owners, and confirm current control owners. |
| Days 31-60 | Monitoring, Vendor Risk, and Evidence Improvements | Expand logging coverage, complete vendor access reviews, standardize access review evidence, and centralize audit evidence. |
| Days 61-90 | Testing, Validation, and Executive Reporting | Conduct incident response tabletop exercise, validate PCI segmentation, complete backup restoration testing, and report progress to leadership. |

## Detailed Remediation Plan

| Remediation ID | Related Finding | Risk Rating | Remediation Action | Owner | Target Date | Validation Method | Status |
|---|---|---|---|---|---|---|---|
| REM-001 | Privileged accounts not fully protected by MFA. | High | Enforce MFA for all privileged accounts and document any approved exceptions. | IAM Manager | Day 30 | Review MFA enrollment report and privileged account list. | Planned |
| REM-002 | Critical vulnerabilities exceeding SLA. | High | Identify overdue vulnerabilities and create escalation procedures for unresolved critical findings. | Infrastructure Manager | Day 30 | Review vulnerability tickets and SLA report. | Planned |
| REM-003 | Incomplete access review documentation. | Medium | Create a standard access review template requiring manager and system owner approval. | GRC Manager | Day 45 | Review completed access review evidence. | Planned |
| REM-004 | Incomplete SIEM logging coverage. | High | Add missing critical systems to SIEM log collection and update the log source inventory. | Security Operations Manager | Day 60 | Review SIEM log source inventory and dashboard evidence. | Planned |
| REM-005 | Vendor access reviews incomplete. | Medium | Perform vendor access review and document owner approval for vendor accounts. | Vendor Risk Manager | Day 60 | Review vendor access review report and approval evidence. | Planned |
| REM-006 | Incident response tabletop testing not completed. | Medium | Conduct an incident response tabletop exercise and document lessons learned. | Security Operations Manager | Day 75 | Review tabletop exercise report and attendance records. | Planned |
| REM-007 | PCI segmentation evidence incomplete. | High | Perform PCI segmentation validation and retain network diagrams, firewall rules, and test results. | Network Security Manager | Day 90 | Review segmentation test results and firewall evidence. | Planned |
| REM-008 | Backup restoration testing incomplete. | High | Perform backup restoration testing for critical systems and retain test evidence. | Infrastructure Manager | Day 90 | Review restoration test records and recovery screenshots. | Planned |
| REM-009 | Data classification practices inconsistent. | Medium | Publish a data classification standard and communicate handling requirements to business teams. | GRC Manager | Day 90 | Review approved standard and training communication. | Planned |
| REM-010 | Asset inventory may not include all cloud assets. | Medium | Reconcile asset inventory with cloud resources and update ownership records. | Cloud Security Manager | Day 90 | Review updated asset inventory and cloud export. | Planned |

## Management Reporting Cadence

Remediation progress should be reported to leadership on a monthly basis.

Each status report should include:

- Completed remediation actions
- Overdue remediation actions
- Risks requiring management decisions
- Blockers or resource needs
- Updated risk ratings
- Evidence collected
- Target dates for remaining items

## Success Criteria

The 90-day remediation plan will be considered successful when:

- All privileged accounts are protected by MFA.
- Critical vulnerability backlog is documented and actively tracked.
- SIEM logging includes all critical systems.
- Vendor access reviews are completed and documented.
- Incident response tabletop testing is completed.
- Backup restoration testing is completed.
- PCI segmentation evidence is collected and retained.
- Management receives a remediation status report.

## Summary

This 90-day remediation plan provides a structured path to reduce risk, improve control effectiveness, and strengthen audit readiness.

The plan should be tracked through the POA&M and reviewed by management until all remediation activities are complete.
