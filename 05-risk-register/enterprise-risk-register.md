# Enterprise Risk Register

## Purpose

This enterprise risk register documents cybersecurity, compliance, operational, and third-party risks identified during the BayouTrust Digital Bank GRC assessment.

The purpose of this register is to demonstrate how risks are identified, scored, assigned, prioritized, and tracked through treatment.

## Risk Scoring

Risk is scored using likelihood and impact.

**Risk Score = Likelihood x Impact**

| Risk Score | Risk Rating |
|---|---|
| 1-5 | Low |
| 6-10 | Medium |
| 11-15 | High |
| 16-25 | Critical |

## Risk Register

| Risk ID | Risk Statement | Category | Likelihood | Impact | Score | Rating | Risk Owner | Treatment | Recommended Action | Status |
|---|---|---|---:|---:|---:|---|---|---|---|---|
| R-001 | Privileged accounts may not be protected by multi-factor authentication. | Identity and Access Management | 4 | 5 | 20 | Critical | IAM Manager | Mitigate | Enforce MFA for all privileged accounts and document approved exceptions. | Open |
| R-002 | Critical vulnerabilities may not be remediated within required timelines. | Vulnerability Management | 4 | 4 | 16 | Critical | Infrastructure Manager | Mitigate | Create escalation process for overdue critical vulnerabilities. | Open |
| R-003 | Logging may not provide full visibility into critical security events. | Logging and Monitoring | 4 | 4 | 16 | Critical | Security Operations Manager | Mitigate | Expand SIEM log collection to all critical systems. | Open |
| R-004 | PCI segmentation evidence may be incomplete. | PCI Readiness | 3 | 5 | 15 | High | Network Security Manager | Mitigate | Perform PCI segmentation validation and retain supporting evidence. | Open |
| R-005 | Backup restoration testing may not be performed or documented consistently. | Business Continuity | 3 | 5 | 15 | High | Infrastructure Manager | Mitigate | Perform restoration testing and retain test evidence. | Open |
| R-006 | Vendor access may not be reviewed on a regular basis. | Vendor Risk Management | 3 | 4 | 12 | High | Vendor Risk Manager | Mitigate | Establish quarterly vendor access reviews. | Open |
| R-007 | Incident response procedures may not be tested annually. | Incident Response | 3 | 4 | 12 | High | Security Operations Manager | Mitigate | Conduct annual incident response tabletop exercises. | Open |
| R-008 | User access reviews may not be fully documented. | Access Governance | 3 | 4 | 12 | High | GRC Manager | Mitigate | Standardize access review templates and approval evidence. | Open |
| R-009 | Asset inventory may not include all cloud assets. | Asset Management | 3 | 4 | 12 | High | Cloud Security Manager | Mitigate | Reconcile asset inventory with cloud resources. | Open |
| R-010 | Data classification practices may be inconsistent across business units. | Data Protection | 3 | 4 | 12 | High | GRC Manager | Mitigate | Publish and communicate a data classification standard. | Open |
| R-011 | Vendor security documentation may not be current for all high-risk vendors. | Third-Party Risk | 3 | 4 | 12 | High | Vendor Risk Manager | Mitigate | Request updated SOC 2 reports, questionnaires, and security documentation. | Open |
| R-012 | Security awareness evidence may be incomplete. | Security Awareness | 2 | 3 | 6 | Medium | GRC Manager | Mitigate | Track training completion and retain evidence. | Open |
| R-013 | Configuration standards may not be consistently applied across systems. | Configuration Management | 3 | 4 | 12 | High | Infrastructure Manager | Mitigate | Define secure configuration baselines and validate compliance. | Open |
| R-014 | Change management evidence may not fully support control expectations. | Change Management | 2 | 4 | 8 | Medium | IT Operations Manager | Mitigate | Improve change approval and testing documentation. | Open |
| R-015 | Cloud administrative activity may not be fully monitored. | Cloud Security | 3 | 4 | 12 | High | Cloud Security Manager | Mitigate | Enable cloud audit logs and route alerts to SIEM. | Open |

## Risk Summary by Rating

| Risk Rating | Count |
|---|---:|
| Critical | 3 |
| High | 10 |
| Medium | 2 |
| Low | 0 |

## Risk Summary by Category

| Category | Count |
|---|---:|
| Identity and Access Management | 1 |
| Vulnerability Management | 1 |
| Logging and Monitoring | 1 |
| PCI Readiness | 1 |
| Business Continuity | 1 |
| Vendor Risk Management | 1 |
| Incident Response | 1 |
| Access Governance | 1 |
| Asset Management | 1 |
| Data Protection | 1 |
| Third-Party Risk | 1 |
| Security Awareness | 1 |
| Configuration Management | 1 |
| Change Management | 1 |
| Cloud Security | 1 |

## Top Risk Themes

The top risk themes identified during the assessment are:

1. Access control and privileged account protection.
2. Vulnerability remediation timeliness.
3. Logging and monitoring coverage.
4. Evidence quality and audit readiness.
5. Vendor and third-party access governance.
6. Backup and recovery validation.
7. Payment environment segmentation.

## Recommended Management Actions

Management should take the following actions:

- Assign risk owners for all high and critical risks.
- Track remediation through the POA&M.
- Review risk status monthly.
- Escalate overdue high-risk remediation items.
- Validate evidence before closing risks.
- Update residual risk after remediation.
- Report progress to executive leadership.

## Summary

The enterprise risk register provides a structured view of cybersecurity and compliance risks across BayouTrust Digital Bank.

This register supports risk prioritization, remediation planning, POA&M tracking, audit readiness, and executive reporting.
