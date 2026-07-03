# PCI Readiness Checklist

## Purpose

This document provides a PCI DSS readiness checklist for BayouTrust Digital Bank.

The purpose is to demonstrate how payment security requirements can be reviewed, documented, and connected to GRC assessment activities.

## PCI Readiness Overview

PCI DSS readiness focuses on protecting cardholder data and the cardholder data environment.

This checklist is not a formal PCI DSS assessment. It is a portfolio example showing how a GRC analyst may prepare for PCI readiness conversations, evidence collection, and remediation planning.

## PCI Readiness Status Definitions

| Status | Definition |
|---|---|
| Ready | Control and evidence appear complete for readiness purposes. |
| Partially Ready | Control exists, but documentation or evidence needs improvement. |
| Not Ready | Control or required evidence is missing. |
| Not Tested | Control area was not tested in this assessment. |

## PCI Readiness Checklist

| PCI Area | Control Topic | Example Evidence | Status | Notes |
|---|---|---|---|---|
| Requirement 1 | Network security controls and segmentation | Network diagrams, firewall rules, segmentation testing evidence | Not Ready | Segmentation testing evidence is missing. |
| Requirement 2 | Secure configurations | Configuration baselines, hardening standards | Partially Ready | Additional baseline evidence is needed. |
| Requirement 3 | Stored account data protection | Data inventory, encryption evidence, retention procedure | Partially Ready | Data storage evidence should be validated. |
| Requirement 4 | Encryption during transmission | TLS configuration, encryption standard | Ready | Encryption evidence was provided. |
| Requirement 5 | Malware protection | Endpoint protection reports, malware alerts | Partially Ready | More complete reporting is needed. |
| Requirement 6 | Secure systems and software | Vulnerability scans, patch reports, remediation tickets | Partially Ready | Critical vulnerabilities exceeded SLA. |
| Requirement 7 | Restrict access by business need | Access control matrix, user access reviews | Partially Ready | Access review evidence is incomplete. |
| Requirement 8 | Identify users and authenticate access | MFA reports, identity provider settings | Partially Ready | Privileged MFA gaps remain. |
| Requirement 9 | Restrict physical access | Physical access logs, visitor records | Not Tested | Physical security is out of scope. |
| Requirement 10 | Log and monitor access | SIEM dashboards, log source inventory, alert reviews | Partially Ready | Critical systems are missing from SIEM. |
| Requirement 11 | Test security of systems and networks | Vulnerability scans, segmentation testing, testing records | Partially Ready | Segmentation testing is missing. |
| Requirement 12 | Security policy and program management | Security policies, risk register, training records | Partially Ready | Policies exist, but evidence should be strengthened. |

## Key PCI Readiness Gaps

The major PCI readiness gaps are:

1. PCI segmentation testing evidence is missing.
2. Privileged account MFA coverage is incomplete.
3. Critical vulnerability remediation exceeded SLA.
4. Access review evidence is incomplete.
5. Logging coverage does not include all critical systems.
6. Secure configuration evidence should be improved.
7. Data storage and cardholder data flow evidence should be validated.

## Recommended PCI Readiness Actions

Recommended actions include:

- Confirm the cardholder data environment scope.
- Update and validate network diagrams.
- Review firewall rules.
- Perform segmentation testing.
- Enforce MFA for privileged accounts.
- Improve vulnerability remediation tracking.
- Complete access reviews.
- Expand SIEM coverage.
- Collect and retain payment security evidence.
- Track open PCI-related gaps through the POA&M.

## Sample PCI Evidence Request List

| PCI Area | Evidence Requested |
|---|---|
| Network Security | Network diagrams, firewall rules, segmentation test results |
| Secure Configurations | Configuration standards and hardening evidence |
| Account Data Protection | Data flow diagrams and encryption evidence |
| Vulnerability Management | Scan reports, patch reports, remediation tickets |
| Access Control | User access reviews and role matrix |
| Authentication | MFA reports and identity provider screenshots |
| Logging | SIEM log source inventory and alert review records |
| Security Testing | Vulnerability scans and segmentation validation |
| Policy | Security policies and annual review evidence |

## Summary

BayouTrust Digital Bank is partially ready from a PCI readiness perspective.

The highest-priority PCI-related actions are segmentation validation, privileged MFA enforcement, vulnerability remediation tracking, access review documentation, and improved logging coverage.
