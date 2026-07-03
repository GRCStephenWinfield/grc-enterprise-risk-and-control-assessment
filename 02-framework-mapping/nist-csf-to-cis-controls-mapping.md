# NIST CSF to CIS Controls Mapping

## Purpose

This document maps selected NIST Cybersecurity Framework 2.0 outcomes to related CIS Controls v8.1 safeguards.

The purpose is to demonstrate how high-level cybersecurity outcomes can be supported by prioritized cybersecurity safeguards.

## Mapping Overview

NIST CSF helps organize cybersecurity risk management outcomes. CIS Controls provide practical safeguards that organizations can implement to reduce cybersecurity risk.

## NIST CSF to CIS Controls Mapping

| Control Area | NIST CSF Function | NIST CSF Category | Related CIS Controls | Example Evidence |
|---|---|---|---|---|
| Asset Inventory | Identify | ID.AM | CIS 1, CIS 2 | Hardware inventory, software inventory, cloud asset export |
| Data Protection | Protect | PR.DS | CIS 3 | Data classification standard, encryption settings, DLP evidence |
| Secure Configuration | Protect | PR.PS | CIS 4 | Baseline configuration, configuration review results |
| Account Management | Protect | PR.AA | CIS 5 | User account list, access review evidence |
| Access Control Management | Protect | PR.AA | CIS 6 | MFA report, role-based access matrix, privileged access list |
| Vulnerability Management | Identify / Protect | ID.RA, PR.PS | CIS 7 | Vulnerability scan reports, remediation tickets |
| Audit Log Management | Detect | DE.CM | CIS 8 | SIEM dashboards, log source inventory, alert review records |
| Email and Browser Protection | Protect | PR.PS | CIS 9 | Email security settings, browser configuration policy |
| Malware Defenses | Protect / Detect | PR.PS, DE.CM | CIS 10 | Endpoint protection reports, malware alert records |
| Data Recovery | Recover | RC.RP | CIS 11 | Backup reports, restoration test results |
| Network Infrastructure | Protect / Detect | PR.IR, DE.CM | CIS 12 | Firewall rules, network diagrams, router configuration evidence |
| Network Monitoring | Detect | DE.CM | CIS 13 | Network monitoring alerts, IDS/IPS reports |
| Security Awareness | Protect | PR.AT | CIS 14 | Training completion report, awareness materials |
| Service Provider Management | Govern | GV.SC | CIS 15 | Vendor risk assessments, vendor contracts, access reviews |
| Application Security | Protect | PR.PS | CIS 16 | Secure SDLC procedure, application scan results |
| Incident Response | Respond | RS.MA, RS.CO | CIS 17 | Incident response plan, tabletop exercise evidence |
| Penetration Testing | Identify | ID.RA | CIS 18 | Penetration test summary, remediation tracking |

## Example Use Case

If the assessment identifies incomplete asset inventory, the control mapping may look like this:

| Item | Example |
|---|---|
| NIST CSF Category | ID.AM |
| CIS Controls | CIS 1 and CIS 2 |
| Risk | Unknown assets may not be patched, monitored, or protected. |
| Evidence Needed | Hardware inventory, software inventory, cloud asset export |
| Remediation | Reconcile asset inventory with cloud and endpoint management tools. |

## Assessment Use

This mapping supports:

- Practical safeguard selection
- Control assessment planning
- Evidence request development
- Risk prioritization
- Gap analysis
- Remediation roadmap development
- Audit readiness

## Summary

Mapping NIST CSF to CIS Controls helps translate cybersecurity outcomes into practical safeguards.

This is useful for organizations that want a prioritized and action-oriented approach to reducing risk.
