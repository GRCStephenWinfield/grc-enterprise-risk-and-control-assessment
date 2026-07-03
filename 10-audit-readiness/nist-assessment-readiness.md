# NIST Assessment Readiness

## Purpose

This document provides a NIST-based assessment readiness checklist for BayouTrust Digital Bank.

The purpose is to demonstrate how NIST CSF and NIST SP 800-53 can be used to organize assessment readiness, evidence requests, control testing, and remediation planning.

## NIST Readiness Overview

This readiness review uses the NIST Cybersecurity Framework functions as a high-level structure:

- Govern
- Identify
- Protect
- Detect
- Respond
- Recover

Selected NIST SP 800-53 control families are used to support more detailed control assessment and evidence planning.

## Readiness Status Definitions

| Status | Definition |
|---|---|
| Ready | Control and evidence are complete for readiness purposes. |
| Partially Ready | Control exists, but evidence, documentation, or monitoring needs improvement. |
| Not Ready | Control or required evidence is missing. |
| Not Tested | Control area was not reviewed in this assessment. |

## NIST Readiness Checklist

| NIST Function | Control Area | Related NIST 800-53 Examples | Example Evidence | Status |
|---|---|---|---|---|
| Govern | Cybersecurity governance and oversight | PM-1, PM-9, RA-3 | Policies, risk register, management review records | Ready |
| Govern | Supply chain risk management | SR-3, SR-5 | Vendor assessments, vendor access reviews | Partially Ready |
| Identify | Asset management | CM-8 | Asset inventory, cloud asset export | Partially Ready |
| Identify | Risk assessment | RA-3, RA-5 | Risk register, vulnerability scans | Ready |
| Protect | Access control | AC-2, AC-3, AC-6 | Access reviews, privileged account list | Partially Ready |
| Protect | Identification and authentication | IA-2 | MFA reports, identity provider settings | Partially Ready |
| Protect | Awareness and training | AT-2 | Training completion reports | Partially Ready |
| Protect | Data protection | SC-8, SC-13 | Encryption standards, data classification standard | Partially Ready |
| Protect | Configuration management | CM-2, CM-6 | Configuration baselines, configuration evidence | Partially Ready |
| Detect | Audit logging and monitoring | AU-2, AU-6, SI-4 | SIEM dashboards, log source inventory | Partially Ready |
| Respond | Incident response | IR-4, IR-6, IR-8 | Incident response plan, tabletop exercise evidence | Partially Ready |
| Recover | Contingency planning and recovery | CP-2, CP-4, CP-9 | Backup reports, restoration testing evidence | Partially Ready |

## Key NIST Readiness Gaps

The major NIST readiness gaps are:

1. Privileged account MFA coverage is incomplete.
2. Cloud asset inventory requires reconciliation.
3. SIEM coverage does not include all critical systems.
4. Vendor access reviews are incomplete.
5. Incident response tabletop testing evidence is missing.
6. Backup restoration testing evidence is incomplete.
7. Configuration baseline evidence needs improvement.

## Recommended NIST Readiness Actions

Recommended actions include:

- Update the asset inventory.
- Enforce MFA for privileged accounts.
- Complete user and vendor access reviews.
- Expand SIEM log collection.
- Conduct incident response tabletop testing.
- Perform backup restoration testing.
- Improve secure configuration evidence.
- Track weaknesses through the POA&M.
- Report NIST readiness status to management.

## Example NIST Evidence Requests

| Control Family | Evidence Requested |
|---|---|
| Access Control | User access reviews, privileged account list, approval records |
| Identification and Authentication | MFA reports, identity provider screenshots |
| Risk Assessment | Risk register, scan reports, risk scoring methodology |
| Audit and Accountability | SIEM dashboards, log source inventory, alert records |
| Incident Response | IR plan, tabletop exercise report, lessons learned |
| Contingency Planning | Backup reports, restoration testing evidence |
| Configuration Management | Secure configuration baselines, configuration review results |
| Supply Chain Risk | Vendor risk assessments, vendor access review evidence |

## Summary

BayouTrust Digital Bank has a developing NIST-based control environment.

The organization should improve evidence quality, access governance, logging coverage, incident response testing, backup validation, and vendor risk management to strengthen NIST assessment readiness.
