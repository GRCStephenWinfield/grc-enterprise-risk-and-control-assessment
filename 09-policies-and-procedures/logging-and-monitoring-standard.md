# Logging and Monitoring Standard

## Purpose

The purpose of this Logging and Monitoring Standard is to define requirements for collecting, retaining, reviewing, and monitoring security logs for BayouTrust Digital Bank systems.

This standard supports threat detection, incident response, audit readiness, regulatory compliance, and operational visibility.

## Scope

This standard applies to:

- Cloud environments
- Banking applications
- Payment systems
- Identity platforms
- Network devices
- Servers
- Databases
- Security tools
- Administrative systems
- Critical business applications
- Vendor-managed systems, where applicable

## Objectives

The objectives of logging and monitoring are to:

- Detect unauthorized activity.
- Support incident response investigations.
- Maintain visibility into critical systems.
- Support audit and compliance requirements.
- Identify suspicious behavior.
- Monitor privileged activity.
- Retain logs for review and investigation.

## Log Source Requirements

The following systems should send logs to the centralized logging or SIEM platform where technically feasible:

| Log Source | Example Events |
|---|---|
| Identity Provider | Login attempts, MFA failures, password changes, privileged access activity. |
| Cloud Platforms | Administrative activity, configuration changes, access events, security alerts. |
| Firewalls | Allowed traffic, denied traffic, rule changes, suspicious connections. |
| Servers | Authentication events, system changes, security alerts, service failures. |
| Databases | Administrative access, failed login attempts, sensitive data access. |
| Banking Applications | Login activity, transaction-related events, administrative actions. |
| Payment Systems | Access to cardholder data environment, system changes, authentication events. |
| Endpoint Security Tools | Malware alerts, suspicious process execution, blocked activity. |
| Vulnerability Tools | Scan results, critical findings, remediation status. |

## Required Security Events

The organization should collect and monitor logs for events such as:

- Failed login attempts
- Successful privileged logins
- MFA failures
- Account lockouts
- New privileged account creation
- Access control changes
- Firewall rule changes
- Cloud configuration changes
- Malware detections
- Suspicious network activity
- Data access anomalies
- Security tool alerts
- Disabled security controls
- Changes to logging settings

## Log Review Requirements

Security logs should be reviewed based on risk and system criticality.

Recommended review expectations:

| Log Type | Recommended Review |
|---|---|
| Critical security alerts | As soon as practical |
| Privileged access activity | Regular review |
| Authentication anomalies | Regular review |
| Firewall and network alerts | Regular review |
| Cloud security alerts | Regular review |
| Payment environment alerts | Regular review |
| General system logs | As needed for investigation |

## Log Retention

Logs should be retained according to business, legal, regulatory, and compliance requirements.

Recommended retention expectations:

| Log Category | Recommended Retention |
|---|---|
| Critical security logs | At least 1 year |
| Payment environment logs | According to PCI DSS requirements |
| Identity and access logs | At least 1 year |
| Incident-related logs | Retain according to investigation and legal requirements |
| General operational logs | Based on business need and storage capacity |

## Monitoring and Alerting

The organization should create monitoring alerts for high-risk events.

Examples include:

- Multiple failed logins
- Login from unusual location
- Privileged account activity
- MFA bypass or failure patterns
- New administrator account creation
- Security group changes
- Firewall rule changes
- Critical malware alerts
- Suspicious cloud activity
- Unauthorized access attempts
- Disabled logging or monitoring tools

## SIEM Log Source Inventory

The security team should maintain a log source inventory.

The inventory should include:

- System name
- System owner
- Log source type
- Criticality
- Data classification
- Whether logs are sent to SIEM
- Last validation date
- Monitoring use cases
- Retention requirements

## Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Security Operations Team | Monitor alerts, review logs, and investigate suspicious activity. |
| System Owners | Ensure critical systems generate required logs. |
| Cloud Security Team | Monitor cloud activity and configuration changes. |
| Network Team | Ensure network devices generate and forward logs. |
| GRC Team | Review logging evidence for audit and compliance readiness. |
| Management | Review logging gaps and approve required resources. |

## Logging Gaps

Logging gaps should be documented and tracked.

Examples of logging gaps include:

- Critical systems not sending logs to SIEM
- Missing privileged activity logs
- Incomplete cloud activity logging
- Logs retained for too short a period
- No documented alert review process
- No owner assigned to log source validation

## Compliance Mapping

This standard supports requirements from:

- NIST Cybersecurity Framework
- NIST SP 800-53
- CIS Controls
- SOC 2 Trust Services Criteria
- PCI DSS

## Review Frequency

This standard should be reviewed at least annually or when major changes occur to systems, monitoring tools, regulatory expectations, or the threat environment.

## Summary

Logging and monitoring help the organization detect threats, investigate incidents, support audits, and maintain visibility into critical systems.

A strong logging and monitoring process is essential for cybersecurity operations, GRC, and compliance readiness.
