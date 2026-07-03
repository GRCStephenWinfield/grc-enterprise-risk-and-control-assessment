# POA&M Template

## Purpose

This Plan of Action and Milestones template is used to track weaknesses, findings, remediation activities, owners, due dates, and validation steps.

A POA&M helps ensure that identified control gaps are formally documented and remediated through a structured process.

## POA&M Status Definitions

| Status | Definition |
|---|---|
| Open | Remediation has not started or is still in progress. |
| In Progress | Remediation activities are actively being worked. |
| Completed | Remediation has been completed and is ready for validation. |
| Validated | Remediation has been tested and confirmed effective. |
| Risk Accepted | Management has formally accepted the risk. |
| Delayed | Remediation has been delayed past the target date. |

## Priority Definitions

| Priority | Definition |
|---|---|
| High | Significant risk requiring near-term remediation. |
| Medium | Moderate risk that should be remediated through normal governance processes. |
| Low | Lower risk that can be addressed as part of continuous improvement. |

## POA&M Tracker

| POA&M ID | Finding ID | Weakness Description | Related Framework | Risk Rating | Remediation Action | Owner | Target Date | Status | Validation Method | Notes |
|---|---|---|---|---|---|---|---|---|---|---|
| POAM-001 | F-001 | Example: Some privileged accounts are not protected by MFA. | NIST IA-2, CIS 6, SOC 2 CC6, PCI DSS Req. 8 | High | Enforce MFA for all privileged accounts. | IAM Manager | TBD | Open | Review MFA enrollment report. | Pending owner action. |
| POAM-002 | F-002 | Example: Critical vulnerabilities exceed remediation SLA. | NIST SI-2, CIS 7, SOC 2 CC7, PCI DSS Req. 6 | High | Create escalation process for overdue critical vulnerabilities. | Infrastructure Manager | TBD | Open | Review vulnerability tickets and SLA report. | Pending remediation plan. |
| POAM-003 | F-003 | Example: Vendor access reviews are incomplete. | NIST SR-3, CIS 15, SOC 2 CC9, PCI DSS Req. 12 | Medium | Complete quarterly vendor access review. | Vendor Risk Manager | TBD | Open | Review completed access review evidence. | Pending vendor access list. |

## POA&M Review Cadence

The POA&M should be reviewed regularly by management.

Recommended review cadence:

- Critical and high items: Monthly
- Medium items: Monthly or quarterly
- Low items: Quarterly
- Delayed items: Escalated to management

## Validation Requirements

Before a POA&M item is closed, evidence should be reviewed to confirm that remediation is complete.

Validation evidence may include:

- Screenshots
- System reports
- Ticket records
- Updated policies
- Access review approvals
- Vulnerability scan results
- Testing records
- Management sign-off

## Summary

This POA&M template provides a structured way to track control weaknesses from identification through remediation and validation.
