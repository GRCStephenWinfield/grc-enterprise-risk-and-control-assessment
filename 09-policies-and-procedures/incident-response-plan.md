# Incident Response Plan

## Purpose

The purpose of this Incident Response Plan is to define how BayouTrust Digital Bank identifies, reports, investigates, responds to, and recovers from cybersecurity incidents.

This plan supports timely response to security events that may impact systems, customer data, financial information, payment systems, business operations, or regulatory obligations.

## Scope

This plan applies to incidents involving:

- Corporate systems
- Cloud environments
- Banking applications
- Payment systems
- Employee endpoints
- Customer data
- Vendor-managed systems
- Network infrastructure
- Security monitoring alerts
- Unauthorized access
- Malware or ransomware
- Data exposure or data loss

## Incident Response Objectives

The objectives of incident response are to:

- Detect and report security incidents quickly.
- Contain threats and limit business impact.
- Preserve evidence where appropriate.
- Restore affected systems safely.
- Communicate with required stakeholders.
- Document lessons learned.
- Improve controls after an incident.

## Incident Severity Levels

| Severity | Description | Example |
|---|---|---|
| Critical | Major incident with significant business, customer, legal, regulatory, or operational impact. | Ransomware impacting production banking systems. |
| High | Serious incident affecting critical systems or sensitive data. | Unauthorized access to a privileged account. |
| Medium | Incident with limited impact but requiring investigation and response. | Malware detected on an employee workstation. |
| Low | Minor security event with limited or no confirmed impact. | Blocked phishing email with no user interaction. |

## Incident Response Phases

### 1. Preparation

Preparation activities include:

- Maintaining the incident response plan
- Assigning incident response roles
- Training response team members
- Maintaining contact lists
- Testing the plan through tabletop exercises
- Ensuring tools and evidence repositories are available

### 2. Detection and Analysis

Potential incidents may be detected through:

- SIEM alerts
- Endpoint detection tools
- User reports
- Vendor notifications
- Cloud security alerts
- Vulnerability alerts
- Fraud monitoring
- Help desk tickets
- External notifications

During analysis, the response team should determine:

- What happened
- Which systems are affected
- Whether sensitive data is involved
- Whether the incident is ongoing
- Severity level
- Required escalation path

### 3. Containment

Containment actions may include:

- Disabling compromised accounts
- Blocking malicious IP addresses
- Isolating affected systems
- Revoking tokens or sessions
- Disabling vendor access
- Applying emergency firewall rules
- Preserving logs and evidence

### 4. Eradication

Eradication actions may include:

- Removing malware
- Closing unauthorized access paths
- Applying patches
- Resetting credentials
- Removing persistence mechanisms
- Correcting misconfigurations
- Validating affected systems

### 5. Recovery

Recovery actions may include:

- Restoring systems from clean backups
- Monitoring systems for recurring activity
- Returning systems to production
- Validating system functionality
- Confirming security controls are working
- Communicating recovery status to stakeholders

### 6. Lessons Learned

After the incident is resolved, the organization should conduct a lessons learned review.

The review should document:

- Timeline of events
- Root cause
- Business impact
- Response actions taken
- What worked well
- What needs improvement
- Control improvements
- Policy or procedure updates
- Follow-up remediation actions

## Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Incident Commander | Leads the incident response process and coordinates response activities. |
| Security Operations Team | Investigates alerts, analyzes evidence, and recommends containment actions. |
| IT Operations Team | Supports containment, eradication, recovery, and system restoration. |
| GRC Team | Supports documentation, regulatory readiness, evidence retention, and control improvements. |
| Legal Team | Advises on legal, contractual, and regulatory obligations. |
| Communications Team | Supports internal and external communications when needed. |
| Executive Leadership | Makes business decisions and approves major response actions. |

## Communication Requirements

Incident communications should be clear, timely, and limited to appropriate stakeholders.

Communication may include:

- Internal escalation notices
- Executive updates
- Legal and compliance notifications
- Customer notifications, if required
- Vendor communications
- Regulatory communications, if required

## Evidence Handling

Incident evidence should be preserved where appropriate.

Evidence may include:

- Logs
- Screenshots
- Alert records
- System images
- Network data
- Email headers
- User activity records
- Ticket history
- Timeline documentation

## Tabletop Exercise Requirement

The incident response plan should be tested at least annually through a tabletop exercise.

Tabletop exercises should include:

- Scenario description
- Participant list
- Response decisions
- Communication steps
- Lessons learned
- Improvement actions

## Compliance Mapping

This plan supports requirements from:

- NIST Cybersecurity Framework
- NIST SP 800-53
- CIS Controls
- SOC 2 Trust Services Criteria
- PCI DSS

## Review Frequency

This plan should be reviewed at least annually or after a significant incident, major business change, or major technology change.

## Summary

A documented incident response plan helps the organization respond quickly, reduce impact, preserve evidence, and improve future security operations.

Incident response is a key part of cybersecurity governance, risk management, and audit readiness.
