# SOC 2 to NIST 800-53 Mapping

## Purpose

This document maps selected SOC 2 Trust Services Criteria areas to related NIST SP 800-53 Rev. 5 controls.

The purpose is to demonstrate how SOC 2 readiness activities can align with NIST-based control assessment work.

## Mapping Overview

SOC 2 focuses on controls relevant to service organizations and trust services categories such as security, availability, processing integrity, confidentiality, and privacy.

NIST SP 800-53 provides detailed control families that can support control design, evidence collection, risk assessment, and audit readiness.

## SOC 2 to NIST 800-53 Mapping

| SOC 2 Area | Example Control Topic | Related NIST 800-53 Controls | Example Evidence |
|---|---|---|---|
| CC1 Control Environment | Governance, tone at the top, roles and accountability | PM-1, PM-9, PL-2 | Security policy, governance charter, management review records |
| CC2 Communication and Information | Security responsibilities and communication | AT-2, PL-4, IR-6 | Security awareness records, communication procedures |
| CC3 Risk Assessment | Risk identification and assessment | RA-3, RA-5, PM-9 | Risk register, risk assessment report, vulnerability scans |
| CC4 Monitoring Activities | Ongoing control monitoring | CA-2, CA-7, AU-6 | Control testing results, audit readiness checklist, SIEM review records |
| CC5 Control Activities | Policies, procedures, and control execution | AC-2, CM-2, CM-6, SI-2 | Policies, access reviews, configuration baselines, patch reports |
| CC6 Logical and Physical Access | Access control, authentication, authorization | AC-2, AC-3, AC-6, IA-2 | User access reviews, MFA reports, privileged access lists |
| CC7 System Operations | Security operations, monitoring, incident response | AU-2, AU-6, SI-4, IR-4 | SIEM dashboards, alert reviews, incident response plan |
| CC8 Change Management | Change approval, testing, and implementation | CM-3, CM-4, CM-5 | Change tickets, approvals, testing records |
| CC9 Risk Mitigation | Vendor risk and risk treatment | SR-3, SR-5, RA-3 | Vendor assessments, vendor access reviews, risk treatment plans |
| A1 Availability | Backup, recovery, capacity, resilience | CP-2, CP-4, CP-9 | Backup reports, restoration tests, disaster recovery plans |
| C1 Confidentiality | Protection of confidential information | SC-8, SC-13, MP-5 | Encryption evidence, data classification standard, access controls |

## SOC 2 Readiness Example

| Readiness Area | Example |
|---|---|
| SOC 2 Criterion | CC6 Logical Access |
| NIST Controls | AC-2, AC-3, AC-6, IA-2 |
| Evidence Needed | User access reviews, MFA reports, privileged account list |
| Finding Example | Privileged accounts are not fully protected by MFA. |
| Remediation | Enforce MFA for all privileged accounts and document exceptions. |

## Assessment Use

This mapping supports:

- SOC 2 readiness
- Control assessment
- Evidence planning
- Audit preparation
- Gap analysis
- Risk register development
- POA&M tracking

## Summary

SOC 2 and NIST 800-53 can work together in a GRC assessment.

SOC 2 provides audit-focused trust services criteria, while NIST 800-53 provides detailed control language that can help support control implementation and testing.
