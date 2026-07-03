# Sample Control Results

## Purpose

This document provides sample control assessment results for BayouTrust Digital Bank.

The purpose is to demonstrate how controls are reviewed, tested, rated, and documented during a Governance, Risk, and Compliance assessment.

## Control Rating Definitions

| Rating | Definition |
|---|---|
| Effective | The control is properly designed and operating as expected. |
| Needs Improvement | The control exists but has design or operating weaknesses. |
| Ineffective | The control is missing, poorly designed, or not operating effectively. |
| Not Tested | The control was not tested during this assessment period. |

## Risk Rating Definitions

| Rating | Definition |
|---|---|
| Low | Limited business impact if the control fails. |
| Medium | Moderate business, compliance, or operational impact if the control fails. |
| High | Significant business, compliance, security, or regulatory impact if the control fails. |
| Critical | Severe impact that may result in major financial, operational, legal, or reputational harm. |

## Sample Control Assessment Results

| Control ID | Control Area | Control Description | Framework Mapping | Evidence Reviewed | Result | Risk Rating | Recommendation |
|---|---|---|---|---|---|---|---|
| IAM-001 | Identity and Access Management | Multi-factor authentication is required for all remote access users. | NIST IA-2, CIS 6, SOC 2 CC6, PCI DSS Req. 8 | MFA policy, identity provider screenshots, remote access configuration | Effective | Low | Continue monitoring MFA enforcement and review configuration quarterly. |
| IAM-002 | Privileged Access Management | Privileged accounts must use MFA and be reviewed quarterly. | NIST AC-2, AC-6, IA-2, CIS 5, CIS 6, SOC 2 CC6 | Privileged account list, MFA report, access review evidence | Needs Improvement | High | Enforce MFA for all privileged accounts and document quarterly access reviews. |
| IAM-003 | User Access Reviews | User access reviews are performed for critical systems on a quarterly basis. | NIST AC-2, AC-3, CIS 5, SOC 2 CC6, PCI DSS Req. 7 | Access review reports, manager approvals, user listing exports | Needs Improvement | Medium | Standardize access review evidence and require sign-off from system owners. |
| VM-001 | Vulnerability Management | Vulnerability scans are performed at least monthly for internal and external systems. | NIST RA-5, SI-2, CIS 7, SOC 2 CC7, PCI DSS Req. 6 | Vulnerability scan reports, scan schedule, remediation tickets | Effective | Low | Continue monthly scanning and maintain remediation tracking. |
| VM-002 | Patch Management | Critical vulnerabilities are remediated within the required service level agreement. | NIST SI-2, CIS 7, SOC 2 CC7, PCI DSS Req. 6 | Patch reports, vulnerability tickets, SLA tracking report | Needs Improvement | High | Create escalation procedures for overdue critical vulnerabilities. |
| LOG-001 | Logging and Monitoring | Security logs are collected from critical systems and reviewed by the security team. | NIST AU-2, AU-6, SI-4, CIS 8, SOC 2 CC7, PCI DSS Req. 10 | SIEM dashboards, log source inventory, alert review records | Needs Improvement | High | Expand log coverage to all critical systems and document alert review procedures. |
| IR-001 | Incident Response | The organization maintains a documented incident response plan. | NIST IR-4, IR-6, IR-8, CIS 17, SOC 2 CC7, PCI DSS Req. 12 | Incident response plan, escalation matrix, communication procedure | Effective | Low | Review and update the incident response plan annually. |
| IR-002 | Incident Response Testing | Incident response tabletop exercises are performed annually. | NIST IR-3, IR-4, IR-8, CIS 17, SOC 2 CC7, PCI DSS Req. 12 | Tabletop exercise records, lessons learned, attendance records | Ineffective | Medium | Conduct an annual tabletop exercise and document lessons learned. |
| VRM-001 | Vendor Risk Management | High-risk vendors are assessed before onboarding. | NIST SR-3, SR-5, CIS 15, SOC 2 CC9, PCI DSS Req. 12 | Vendor due diligence checklist, security questionnaires, contract review records | Effective | Low | Continue requiring security review before onboarding high-risk vendors. |
| VRM-002 | Vendor Access Reviews | Vendor access to systems is reviewed on a regular basis. | NIST AC-2, SR-3, CIS 15, SOC 2 CC9, PCI DSS Req. 12 | Vendor access list, access review evidence, termination tickets | Needs Improvement | Medium | Establish quarterly vendor access reviews and document system owner approval. |
| DP-001 | Data Protection | Sensitive data is encrypted in transit and at rest. | NIST SC-8, SC-13, CIS 3, SOC 2 CC6, PCI DSS Req. 3, Req. 4 | Encryption standard, cloud configuration screenshots, database encryption settings | Effective | Low | Continue monitoring encryption settings for critical systems. |
| BC-001 | Backup and Recovery | Backups are performed regularly for critical systems. | NIST CP-9, CIS 11, SOC 2 A1, PCI DSS Req. 12 | Backup schedules, backup job reports, system inventory | Effective | Low | Continue backup monitoring and review backup failures daily. |
| BC-002 | Backup Restoration Testing | Backup restoration testing is performed and documented. | NIST CP-4, CP-9, CIS 11, SOC 2 A1, PCI DSS Req. 12 | Restoration test records, recovery screenshots, test results | Needs Improvement | High | Perform formal backup restoration testing and retain evidence of results. |
| PCI-001 | PCI Segmentation | The cardholder data environment is segmented from the corporate network. | NIST SC-7, CIS 12, CIS 13, PCI DSS Req. 1 | Network diagram, firewall rules, segmentation testing evidence | Needs Improvement | High | Validate segmentation controls and retain evidence of segmentation testing. |
| GOV-001 | Governance | Cybersecurity policies are reviewed and approved annually. | NIST PM-1, PL-2, CIS 17, SOC 2 CC1, PCI DSS Req. 12 | Policy review records, approval history, policy repository | Effective | Low | Continue annual policy review and maintain approval evidence. |

## Summary of Results

| Result | Count |
|---|---:|
| Effective | 6 |
| Needs Improvement | 8 |
| Ineffective | 1 |
| Not Tested | 0 |

## Key Findings

The assessment identified several control areas requiring improvement:

1. Some privileged accounts are not fully protected by multi-factor authentication.
2. Critical vulnerabilities are not always remediated within required timelines.
3. Logging coverage does not include all critical systems.
4. Vendor access reviews are not consistently documented.
5. Backup restoration testing is not consistently performed or documented.
6. PCI segmentation evidence is incomplete.
7. Incident response tabletop testing has not been completed in the last 12 months.

## Recommended Next Steps

The organization should prioritize remediation based on risk rating, business impact, and compliance exposure.

Recommended next steps include:

- Enforce MFA for all privileged accounts.
- Improve vulnerability remediation tracking and escalation.
- Expand SIEM logging coverage for critical systems.
- Establish quarterly vendor access reviews.
- Conduct annual incident response tabletop testing.
- Perform documented backup restoration testing.
- Validate PCI segmentation and retain testing evidence.
