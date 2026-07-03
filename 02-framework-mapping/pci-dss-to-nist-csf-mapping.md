# PCI DSS to NIST CSF Mapping

## Purpose

This document maps selected PCI DSS v4.0.1 requirement areas to related NIST Cybersecurity Framework 2.0 functions and categories.

The purpose is to demonstrate how payment card security requirements can be connected to broader cybersecurity risk management outcomes.

## Mapping Overview

PCI DSS focuses on protecting payment card data and the cardholder data environment.

NIST CSF provides a broader cybersecurity risk management structure that can help organize payment security controls into governance, protection, detection, response, and recovery outcomes.

## PCI DSS to NIST CSF Mapping

| PCI DSS Area | Payment Security Topic | Related NIST CSF Function | Related NIST CSF Category | Example Evidence |
|---|---|---|---|---|
| Requirement 1 | Network security controls and firewall configuration | Protect | PR.IR, PR.PS | Network diagrams, firewall rules, segmentation evidence |
| Requirement 2 | Secure configurations | Protect | PR.PS | Configuration baselines, hardening standards, configuration review evidence |
| Requirement 3 | Protect stored account data | Protect | PR.DS | Encryption settings, data storage inventory, data retention procedures |
| Requirement 4 | Protect cardholder data during transmission | Protect | PR.DS | TLS configuration, encryption standard, secure transmission evidence |
| Requirement 5 | Protection against malware | Protect / Detect | PR.PS, DE.CM | Endpoint protection reports, malware alerts |
| Requirement 6 | Secure systems and software | Identify / Protect | ID.RA, PR.PS | Vulnerability scans, patch reports, secure development evidence |
| Requirement 7 | Restrict access by business need to know | Protect | PR.AA | Access control matrix, user access reviews |
| Requirement 8 | Identify users and authenticate access | Protect | PR.AA | MFA reports, identity provider settings, authentication policy |
| Requirement 9 | Restrict physical access | Protect | PR.PS | Physical access review records, visitor logs |
| Requirement 10 | Log and monitor access | Detect | DE.CM | SIEM dashboards, log source inventory, alert reviews |
| Requirement 11 | Test security of systems and networks | Identify / Detect | ID.RA, DE.CM | Vulnerability scans, segmentation tests, penetration test summaries |
| Requirement 12 | Security policy and program management | Govern | GV.OC, GV.RM, GV.OV | Security policies, risk register, governance records |

## PCI Readiness Example

| Item | Example |
|---|---|
| PCI Requirement | Requirement 1 |
| NIST CSF Category | PR.IR, PR.PS |
| Risk | Cardholder data environment may not be properly segmented. |
| Evidence Needed | Network diagram, firewall rules, segmentation testing results |
| Finding Example | Segmentation testing evidence is missing. |
| Remediation | Perform segmentation validation and retain test evidence. |

## Assessment Use

This mapping supports:

- PCI readiness
- Payment security control assessment
- Evidence request planning
- Risk register development
- Gap analysis
- Remediation planning
- Audit readiness reporting

## Summary

Mapping PCI DSS to NIST CSF helps connect payment security requirements to broader cybersecurity risk management outcomes.

This allows the organization to treat PCI readiness as part of enterprise risk management rather than a separate compliance-only activity.
