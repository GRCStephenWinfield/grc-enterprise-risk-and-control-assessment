# Management Action Plan

## Purpose

This Management Action Plan summarizes the actions leadership should take to address the highest-priority findings identified during the BayouTrust Digital Bank GRC assessment.

The purpose of this document is to demonstrate how GRC findings can be translated into business actions, ownership, due dates, and leadership reporting.

## Management Action Summary

| Action ID | Related Finding | Business Risk | Action Required | Owner | Priority | Target Date | Status |
|---|---|---|---|---|---|---|---|
| MAP-001 | Privileged accounts not fully protected by MFA. | Unauthorized privileged access could lead to system compromise or data exposure. | Enforce MFA for all privileged accounts and document approved exceptions. | IAM Manager | High | Day 30 | Planned |
| MAP-002 | Critical vulnerabilities exceeding SLA. | Unpatched systems may increase the likelihood of exploitation or service disruption. | Create critical vulnerability backlog and escalation process. | Infrastructure Manager | High | Day 30 | Planned |
| MAP-003 | Incomplete SIEM logging coverage. | Security events may go undetected if critical systems are not monitored. | Expand SIEM logging to all critical systems and validate log sources. | Security Operations Manager | High | Day 60 | Planned |
| MAP-004 | Vendor access reviews incomplete. | Vendor accounts may retain unnecessary access to sensitive systems. | Complete vendor access review and require system owner approval. | Vendor Risk Manager | Medium | Day 60 | Planned |
| MAP-005 | Incident response tabletop not completed. | Response teams may be unprepared during a real incident. | Conduct annual incident response tabletop exercise. | Security Operations Manager | Medium | Day 75 | Planned |
| MAP-006 | PCI segmentation evidence incomplete. | Incomplete segmentation evidence may create payment security and audit readiness risk. | Perform PCI segmentation validation and retain evidence. | Network Security Manager | High | Day 90 | Planned |
| MAP-007 | Backup restoration testing incomplete. | Recovery capability may not be proven during an outage or ransomware event. | Perform backup restoration testing and document results. | Infrastructure Manager | High | Day 90 | Planned |

## Leadership Priorities

Leadership should focus on the following areas first:

1. Reduce privileged access risk.
2. Reduce exposure from critical vulnerabilities.
3. Improve detection and monitoring coverage.
4. Validate payment environment segmentation.
5. Confirm backup recovery capabilities.
6. Improve vendor access governance.
7. Test incident response readiness.

## Resource Considerations

Management may need to provide support for:

- IAM engineering work
- Vulnerability remediation capacity
- SIEM onboarding and monitoring resources
- Vendor risk review coordination
- Incident response tabletop planning
- Network segmentation validation
- Backup restoration testing

## Reporting Cadence

Progress should be reported to leadership monthly until high-risk findings are remediated.

Monthly reporting should include:

- Completed actions
- Open actions
- Overdue actions
- Blockers
- Resource needs
- Updated risk rating
- Evidence collected
- Decisions requiring leadership approval

## Success Measures

Success should be measured by:

- Reduction in high-risk findings
- Completion of remediation milestones
- Improved audit readiness status
- Evidence collected for key controls
- Decrease in overdue vulnerabilities
- Increased SIEM coverage
- Completion of incident response testing
- Validation of backup recovery capability

## Summary

The Management Action Plan helps leadership understand what needs to be done, who owns the work, and when remediation should be completed.

This document connects GRC assessment results to business execution and executive accountability.
