# SOC 2 Readiness Checklist

## Purpose

This document provides a SOC 2 readiness checklist for BayouTrust Digital Bank.

The purpose is to demonstrate how a GRC analyst can prepare an organization for a SOC 2 readiness review by identifying control areas, evidence needs, gaps, and remediation actions.

## SOC 2 Readiness Overview

SOC 2 readiness focuses on whether the organization has controls that support the Trust Services Criteria.

This checklist focuses primarily on security, availability, and confidentiality-related areas.

## SOC 2 Readiness Status Definitions

| Status | Definition |
|---|---|
| Ready | Control and evidence are complete and ready for review. |
| Partially Ready | Control exists, but evidence or process improvement is needed. |
| Not Ready | Control or evidence is missing. |
| Not Tested | Control area was not reviewed during this assessment. |

## SOC 2 Readiness Checklist

| SOC 2 Area | Control Topic | Example Evidence | Status | Notes |
|---|---|---|---|---|
| CC1 Control Environment | Governance policies are documented and approved. | Security policies, approval records, governance documents | Ready | Policy approval evidence exists. |
| CC2 Communication and Information | Security responsibilities are communicated to personnel. | Security awareness records, communication procedures | Partially Ready | Training evidence should be improved. |
| CC3 Risk Assessment | Cybersecurity risks are identified and assessed. | Risk register, risk scoring methodology, risk review records | Ready | Risk register has been created. |
| CC4 Monitoring Activities | Controls are monitored and reviewed. | Control testing results, audit readiness checklist, management reports | Partially Ready | Monitoring should be more formalized. |
| CC5 Control Activities | Control activities are documented and assigned. | Control matrix, control owner list, policies | Partially Ready | Some owner assignments need confirmation. |
| CC6 Logical Access | User access is approved, restricted, and reviewed. | User access reviews, MFA reports, privileged access list | Partially Ready | Privileged MFA gaps remain. |
| CC7 System Operations | Security events are monitored and incidents are managed. | SIEM dashboards, alert reviews, incident response plan | Partially Ready | SIEM coverage and tabletop evidence need improvement. |
| CC8 Change Management | Changes are authorized, tested, and approved. | Change tickets, approval records, testing evidence | Not Tested | Change management was not reviewed in detail. |
| CC9 Risk Mitigation | Vendor and risk mitigation processes exist. | Vendor assessments, vendor access reviews, risk treatment plans | Partially Ready | Vendor access reviews need improvement. |
| A1 Availability | Backup and recovery controls exist. | Backup reports, restoration testing evidence | Partially Ready | Restoration testing evidence is incomplete. |
| C1 Confidentiality | Confidential data is protected. | Data classification standard, encryption evidence, access controls | Partially Ready | Data classification process needs standardization. |

## Key SOC 2 Readiness Gaps

The major SOC 2 readiness gaps are:

1. Privileged accounts are not fully protected by MFA.
2. SIEM logging coverage does not include all critical systems.
3. Incident response tabletop evidence is missing.
4. Vendor access reviews are incomplete.
5. Backup restoration testing evidence is incomplete.
6. Data classification practices need standardization.
7. Change management was not tested during this assessment.

## Recommended SOC 2 Readiness Actions

Recommended actions include:

- Enforce MFA for all privileged accounts.
- Complete quarterly access reviews.
- Expand SIEM logging coverage.
- Conduct an incident response tabletop exercise.
- Complete vendor access reviews.
- Perform backup restoration testing.
- Improve evidence retention.
- Confirm control owners for all SOC 2 control areas.

## Sample SOC 2 Evidence Request List

| Control Area | Evidence Requested |
|---|---|
| Governance | Approved security policies and annual review records |
| Access Control | User access review reports and approval evidence |
| MFA | MFA configuration screenshots and enrollment reports |
| Vendor Risk | Vendor due diligence records and SOC 2 reports |
| Incident Response | Incident response plan and tabletop exercise report |
| Logging | SIEM log source inventory and alert review records |
| Backup and Recovery | Backup job reports and restoration testing evidence |
| Risk Management | Risk register and management review evidence |

## Summary

BayouTrust Digital Bank appears partially ready for a SOC 2 readiness review.

The organization should improve evidence quality, privileged access controls, logging coverage, incident response testing, vendor access reviews, and backup restoration testing before pursuing a formal SOC 2 audit.
