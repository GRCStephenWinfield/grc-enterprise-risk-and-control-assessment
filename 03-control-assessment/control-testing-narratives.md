# Control Testing Narratives

## Purpose

This document provides sample control testing narratives for the BayouTrust Digital Bank GRC assessment.

The purpose is to demonstrate how control testing procedures, evidence reviewed, results, and conclusions can be documented in a clear and professional format.

## Testing Narrative Format

Each control narrative includes:

- Control ID
- Control area
- Control objective
- Testing procedure
- Evidence reviewed
- Testing result
- Conclusion
- Recommendation

## IAM-001: Multi-Factor Authentication for Remote Access

### Control Area

Identity and Access Management

### Control Objective

Confirm that multi-factor authentication is required for users accessing company systems remotely.

### Testing Procedure

The assessment team reviewed the MFA policy, remote access configuration, and identity provider screenshots to determine whether MFA is enabled for remote access users.

### Evidence Reviewed

- MFA policy
- Identity provider configuration screenshot
- Remote access configuration screenshot
- MFA enrollment report

### Testing Result

The evidence showed that MFA is enabled for standard remote access users.

### Conclusion

The control is designed effectively and operating as expected.

### Rating

Effective

### Recommendation

Continue monitoring MFA enforcement and review the configuration on a quarterly basis.

---

## IAM-002: Privileged Account MFA

### Control Area

Privileged Access Management

### Control Objective

Confirm that privileged accounts are protected by multi-factor authentication.

### Testing Procedure

The assessment team reviewed the privileged account list and MFA enrollment report to determine whether all administrative accounts were enrolled in MFA.

### Evidence Reviewed

- Privileged account list
- MFA enrollment report
- Access control policy

### Testing Result

The evidence showed that some privileged accounts were not enrolled in MFA.

### Conclusion

The control exists but is not operating fully as expected.

### Rating

Needs Improvement

### Recommendation

Require MFA for all privileged accounts and document any approved exceptions.

---

## VM-002: Critical Vulnerability Remediation

### Control Area

Vulnerability Management

### Control Objective

Confirm that critical vulnerabilities are remediated within the required service level agreement.

### Testing Procedure

The assessment team reviewed vulnerability scan reports, remediation tickets, and SLA tracking reports to determine whether critical vulnerabilities were remediated within required timelines.

### Evidence Reviewed

- Vulnerability scan report
- Remediation ticket export
- SLA tracking report

### Testing Result

The evidence showed that several critical vulnerabilities exceeded the required remediation timeframe.

### Conclusion

The control exists, but operating effectiveness needs improvement.

### Rating

Needs Improvement

### Recommendation

Create an escalation process for overdue critical vulnerabilities and report overdue items to management.

---

## LOG-001: Security Logging and Monitoring

### Control Area

Logging and Monitoring

### Control Objective

Confirm that critical systems send security logs to the centralized logging or SIEM platform.

### Testing Procedure

The assessment team reviewed the SIEM log source inventory, SIEM dashboards, and alert review records to determine whether critical systems were included in centralized monitoring.

### Evidence Reviewed

- SIEM dashboard screenshot
- Log source inventory
- Alert review records

### Testing Result

The evidence showed that some critical systems were not included in the SIEM log source inventory.

### Conclusion

The control exists, but logging coverage is incomplete.

### Rating

Needs Improvement

### Recommendation

Update the log source inventory and onboard all critical systems to the SIEM where technically feasible.

---

## IR-002: Incident Response Tabletop Exercise

### Control Area

Incident Response

### Control Objective

Confirm that incident response tabletop exercises are performed at least annually.

### Testing Procedure

The assessment team requested the most recent tabletop exercise report, participant list, and lessons learned documentation.

### Evidence Reviewed

- Evidence request tracker
- Incident response plan

### Testing Result

No recent tabletop exercise evidence was provided.

### Conclusion

The control is not operating effectively.

### Rating

Ineffective

### Recommendation

Conduct an annual tabletop exercise and document the scenario, participants, decisions, lessons learned, and improvement actions.

---

## VRM-002: Vendor Access Reviews

### Control Area

Vendor Risk Management

### Control Objective

Confirm that vendor access to company systems is reviewed on a regular basis.

### Testing Procedure

The assessment team reviewed the vendor access list and requested evidence of recent vendor access reviews.

### Evidence Reviewed

- Vendor access list
- Vendor access review request
- Evidence request tracker

### Testing Result

The vendor access list was provided, but approval evidence for the review was incomplete.

### Conclusion

The control exists, but evidence quality and review documentation need improvement.

### Rating

Needs Improvement

### Recommendation

Establish quarterly vendor access reviews and require documented approval from system owners.

---

## BC-002: Backup Restoration Testing

### Control Area

Business Continuity

### Control Objective

Confirm that backup restoration testing is performed and documented for critical systems.

### Testing Procedure

The assessment team requested restoration test records, recovery screenshots, and test result documentation.

### Evidence Reviewed

- Backup job report
- Restoration testing request
- Evidence request tracker

### Testing Result

Backup jobs were running, but restoration testing evidence was incomplete.

### Conclusion

The organization has backup processes in place, but recovery capability has not been fully validated through documented testing.

### Rating

Needs Improvement

### Recommendation

Perform formal backup restoration testing for critical systems and retain evidence of test results.

---

## PCI-001: PCI Segmentation Validation

### Control Area

PCI Readiness

### Control Objective

Confirm that the cardholder data environment is segmented from the corporate network and that segmentation controls are validated.

### Testing Procedure

The assessment team reviewed the network diagram and requested firewall rules and segmentation testing evidence.

### Evidence Reviewed

- Network diagram
- Firewall rule request
- Segmentation testing request

### Testing Result

A network diagram was provided, but segmentation testing evidence was missing.

### Conclusion

The control exists, but evidence is insufficient to validate segmentation effectiveness.

### Rating

Needs Improvement

### Recommendation

Perform segmentation validation and retain network diagrams, firewall rules, test results, and management approval evidence.

## Summary

The control testing narratives show how assessment conclusions are supported by evidence, testing procedures, and documented results.

These narratives help connect control testing to risk ratings, findings, remediation actions, and audit readiness.
