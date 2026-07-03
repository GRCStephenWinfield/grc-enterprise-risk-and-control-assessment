# Audit Readiness Checklist

## Purpose

This document provides an audit readiness checklist for the BayouTrust Digital Bank GRC assessment.

The purpose of this checklist is to demonstrate how an organization can prepare for cybersecurity, compliance, and internal audit activities by organizing controls, evidence, owners, and remediation items.

## Audit Readiness Objectives

The audit readiness process is designed to confirm that:

- Key controls are documented.
- Control owners are assigned.
- Evidence is available and complete.
- Policies and procedures are current.
- Risks and findings are tracked.
- Remediation plans are documented.
- Management understands the organization’s risk posture.

## Audit Readiness Status Definitions

| Status | Definition |
|---|---|
| Ready | Evidence and documentation are complete and ready for audit review. |
| Partially Ready | Some evidence exists, but additional documentation or validation is needed. |
| Not Ready | Evidence is missing, incomplete, or not approved. |
| Not Applicable | The item does not apply to the current assessment scope. |

## General Audit Readiness Checklist

| Checklist ID | Area | Readiness Item | Owner | Status | Notes |
|---|---|---|---|---|---|
| AR-001 | Governance | Cybersecurity policies are current and approved. | GRC Manager | Ready | Annual policy approval evidence is available. |
| AR-002 | Governance | Control owners are identified for major control areas. | GRC Manager | Partially Ready | Some backup control owners need to be confirmed. |
| AR-003 | Risk Management | Risk register is current and includes risk owners. | GRC Manager | Ready | Top risks have been documented. |
| AR-004 | Identity and Access Management | User access review evidence is complete. | IAM Manager | Partially Ready | Some manager approvals are missing. |
| AR-005 | Privileged Access Management | Privileged account list is current. | IAM Manager | Partially Ready | MFA status needs to be verified for all privileged accounts. |
| AR-006 | Vulnerability Management | Vulnerability scan reports are available. | Security Operations Manager | Ready | Recent scan reports were provided. |
| AR-007 | Patch Management | Patch remediation evidence is available. | Infrastructure Manager | Partially Ready | Some critical vulnerabilities exceeded SLA. |
| AR-008 | Logging and Monitoring | SIEM log source inventory is current. | Security Operations Manager | Partially Ready | Critical system coverage needs improvement. |
| AR-009 | Incident Response | Incident response plan is documented. | Security Operations Manager | Ready | Current IR plan was provided. |
| AR-010 | Incident Response | Tabletop exercise evidence is available. | Security Operations Manager | Not Ready | No recent tabletop exercise evidence was provided. |
| AR-011 | Vendor Risk Management | High-risk vendor assessments are documented. | Vendor Risk Manager | Partially Ready | Some vendor reviews are pending. |
| AR-012 | Data Protection | Encryption evidence is available. | Cloud Security Manager | Ready | Encryption standards and configuration evidence were provided. |
| AR-013 | Backup and Recovery | Backup job reports are available. | Infrastructure Manager | Ready | Backup job evidence was provided. |
| AR-014 | Backup and Recovery | Restoration testing evidence is available. | Infrastructure Manager | Partially Ready | Restoration test evidence is incomplete. |
| AR-015 | PCI Readiness | PCI segmentation evidence is available. | Network Security Manager | Not Ready | Segmentation testing evidence is missing. |

## SOC 2 Readiness Checklist

| SOC 2 Area | Readiness Item | Status | Notes |
|---|---|---|---|
| CC1 Control Environment | Governance policies are documented and approved. | Ready | Annual policy review evidence exists. |
| CC2 Communication and Information | Security responsibilities are communicated. | Partially Ready | Security awareness evidence should be improved. |
| CC3 Risk Assessment | Cybersecurity risks are identified and assessed. | Ready | Risk register has been created. |
| CC4 Monitoring Activities | Control monitoring activities are performed. | Partially Ready | Control monitoring should be more formalized. |
| CC5 Control Activities | Security controls are documented and assigned. | Partially Ready | Some control owner assignments need confirmation. |
| CC6 Logical Access | Access controls are implemented. | Partially Ready | Privileged MFA gaps remain. |
| CC7 System Operations | Logging, monitoring, and incident response controls exist. | Partially Ready | SIEM coverage and IR testing need improvement. |
| CC8 Change Management | Change management process exists. | Not Tested | Change management was not tested in this assessment. |
| CC9 Risk Mitigation | Vendor risk and risk treatment activities exist. | Partially Ready | Vendor access reviews need improvement. |

## PCI DSS Readiness Checklist

| PCI Area | Readiness Item | Status | Notes |
|---|---|---|---|
| Network Security Controls | Firewall rules are documented and reviewed. | Partially Ready | Firewall review evidence should be strengthened. |
| Secure Configurations | Secure configuration standards are documented. | Partially Ready | Additional configuration evidence is needed. |
| Account Data Protection | Cardholder data protection controls exist. | Partially Ready | Data flow and storage evidence should be validated. |
| Encryption | Sensitive data is encrypted in transit and at rest. | Ready | Encryption evidence was provided. |
| Vulnerability Management | Vulnerability scans are performed. | Ready | Scan reports were provided. |
| Access Control | Access to cardholder data is restricted. | Partially Ready | Access reviews need stronger documentation. |
| Authentication | MFA is used for applicable access. | Partially Ready | Privileged account MFA gaps remain. |
| Logging and Monitoring | Logs are collected and reviewed. | Partially Ready | SIEM coverage gaps remain. |
| Security Testing | Segmentation testing is performed. | Not Ready | Segmentation testing evidence is missing. |
| Security Policy | Security policies are documented and approved. | Ready | Policy approval evidence was provided. |

## NIST Assessment Readiness Checklist

| NIST Area | Readiness Item | Status | Notes |
|---|---|---|---|
| Identify | Asset inventory and risk register are maintained. | Partially Ready | Cloud assets need reconciliation. |
| Protect | Access control, encryption, and awareness controls are implemented. | Partially Ready | Privileged MFA gap remains. |
| Detect | Logging and monitoring capabilities are in place. | Partially Ready | SIEM coverage needs improvement. |
| Respond | Incident response plan is documented. | Partially Ready | Tabletop testing is missing. |
| Recover | Backup and recovery controls exist. | Partially Ready | Restoration testing evidence is incomplete. |
| Govern | Policies, roles, and risk management processes are documented. | Ready | Governance documentation exists. |

## Sample Auditor Walkthrough Questions

| Area | Sample Question |
|---|---|
| Governance | How does management review and approve cybersecurity policies? |
| Risk Management | How are cybersecurity risks identified, scored, and tracked? |
| IAM | How are new users approved and provisioned? |
| IAM | How are terminated users removed from systems? |
| Privileged Access | How are privileged accounts approved, reviewed, and monitored? |
| Vulnerability Management | How are critical vulnerabilities tracked to closure? |
| Logging and Monitoring | Which systems send logs to the SIEM? |
| Incident Response | When was the last incident response tabletop exercise completed? |
| Vendor Risk | How are high-risk vendors assessed before onboarding? |
| Data Protection | How is sensitive data encrypted and protected? |
| Backup and Recovery | How often are backups tested for restoration? |
| PCI DSS | How is the cardholder data environment segmented and validated? |

## Key Audit Readiness Gaps

The following areas require improvement before a formal audit:

1. Privileged account MFA validation.
2. User access review approval evidence.
3. SIEM log source coverage.
4. Incident response tabletop testing.
5. Vendor access review documentation.
6. Backup restoration testing.
7. PCI segmentation testing evidence.

## Recommended Next Steps

The organization should complete the following actions before a formal audit:

- Validate MFA for all privileged accounts.
- Complete and retain user access review approvals.
- Update the SIEM log source inventory.
- Conduct an incident response tabletop exercise.
- Complete vendor access reviews.
- Perform backup restoration testing.
- Validate PCI segmentation.
- Store all evidence in a centralized repository.
- Review audit readiness status with management.

## Summary

Audit readiness requires more than having controls in place. The organization must also maintain documentation, evidence, ownership, and repeatable processes.

This checklist helps prepare BayouTrust Digital Bank for SOC 2, PCI DSS, NIST-based assessments, and internal audit reviews.
