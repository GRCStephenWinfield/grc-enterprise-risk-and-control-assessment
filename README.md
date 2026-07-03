# grc-enterprise-risk-and-control-assessment

## Reviewer Quick Links

| File | Purpose | Link |
|---|---|---|
| Repository Summary | Short overview of the full GRC portfolio project. | [Open](./repository-summary.md) |
| How to Review This Portfolio | Suggested review path for hiring managers, recruiters, and GRC leaders. | [Open](./how-to-review-this-portfolio.md) |
| Portfolio Completion Checklist | Tracks completed repository sections and deliverables. | [Open](./portfolio-completion-checklist.md) |

## Project Overview

This repository demonstrates a full Governance, Risk, and Compliance assessment for a fictional enterprise organization. The scenario is based on a digital bank, fintech, and technology company environment that must manage cybersecurity risk, regulatory expectations, third-party risk, cloud security, payment security, and executive reporting.

The purpose of this project is to showcase practical GRC skills by walking through the full assessment lifecycle: scoping, framework mapping, control assessment, evidence requests, risk identification, gap analysis, remediation planning, POA&M development, and executive reporting.

## Project Navigation

| Section | Description | Link |
|---|---|---|
| Client Scenario | Fictional company profile and business context. | [Open](./00-client-scenario/company-profile.md) |
| Assessment Scope | Assessment objective, scope, frameworks, and deliverables. | [Open](./01-assessment-scope/assessment-charter.md) |
| Framework Mapping | Control crosswalk across NIST CSF, NIST 800-53, CIS, SOC 2, and PCI DSS. | [Open](./02-framework-mapping/control-crosswalk-summary.md) |
| Risk Register | Top 10 enterprise cybersecurity and compliance risks. | [Open](./05-risk-register/top-10-risks-summary.md) |
| Executive Reporting | Executive-level risk summary, findings, and 90-day action plan. | [Open](./08-executive-reporting/executive-summary.md) |

## Fictional Client Scenario

Company Name: BayouTrust Digital Bank
Industry: Banking, Fintech, and Technology
Company Size: 1,200 employees
Environment: Cloud-hosted banking platform, online customer portal, payment processing systems, internal corporate network, remote workforce, and third-party vendors
Sensitive Data: Customer PII, financial records, payment card data, authentication data, vendor records, and internal business information

BayouTrust Digital Bank is a fictional financial technology company that provides online banking, digital payments, customer account management, and business banking services. The company uses cloud infrastructure, third-party vendors, and internal IT systems to support its operations.


## Frameworks Used

This assessment uses several major cybersecurity and GRC frameworks to demonstrate cross-framework control mapping and risk management.

* NIST Cybersecurity Framework 2.0
* NIST SP 800-53 Rev. 5
* CIS Controls v8.1
* SOC 2 Trust Services Criteria
* PCI DSS v4.0.1
* POA&M methodology
* Enterprise risk management concepts


## Repository Objectives

This repository is designed to demonstrate the ability to:

* Define the scope of a GRC assessment
* Identify business, technology, and compliance risks
* Map cybersecurity controls across multiple frameworks
* Assess control design and operating effectiveness
* Create evidence request lists
* Build a risk register
* Perform a control gap analysis
* Develop a Plan of Action and Milestones
* Create a remediation roadmap
* Prepare executive-level risk reporting
* Support audit readiness activities


## Repository Structure

```text
grc-enterprise-risk-and-control-assessment/
│
├── README.md
│
├── 00-client-scenario/
│   ├── company-profile.md
│   ├── business-overview.md
│   ├── technology-environment.md
│   ├── regulatory-drivers.md
│   └── assumptions-and-limitations.md
│
├── 01-assessment-scope/
│   ├── assessment-charter.md
│   ├── in-scope-systems.md
│   ├── out-of-scope-systems.md
│   ├── stakeholder-list.md
│   └── assessment-methodology.md
│
├── 02-framework-mapping/
│   ├── nist-csf-to-nist-800-53-mapping.xlsx
│   ├── nist-csf-to-cis-controls-mapping.xlsx
│   ├── soc2-to-nist-800-53-mapping.xlsx
│   ├── pci-dss-to-nist-csf-mapping.xlsx
│   └── control-crosswalk-summary.md
│
├── 03-control-assessment/
│   ├── control-assessment-workbook.xlsx
│   ├── control-testing-narratives.md
│   ├── control-rating-methodology.md
│   └── sample-control-results.md
│
├── 04-evidence-request-list/
│   ├── evidence-request-list.xlsx
│   ├── evidence-request-tracker.md
│   └── sample-evidence-review-notes.md
│
├── 05-risk-register/
│   ├── enterprise-risk-register.xlsx
│   ├── risk-scoring-methodology.md
│   ├── risk-heat-map.png
│   └── top-10-risks-summary.md
│
├── 06-gap-analysis/
│   ├── gap-analysis-report.md
│   ├── control-gap-summary.xlsx
│   ├── maturity-assessment.md
│   └── quick-wins.md
│
├── 07-poam-remediation-plan/
│   ├── poam.xlsx
│   ├── remediation-roadmap.md
│   ├── 90-day-remediation-plan.md
│   └── risk-acceptance-template.md
│
├── 08-executive-reporting/
│   ├── executive-summary.md
│   ├── board-risk-report.md
│   ├── risk-dashboard-mockup.png
│   ├── top-findings-summary.md
│   └── management-action-plan.md
│
├── 09-policies-and-procedures/
│   ├── access-control-policy.md
│   ├── vulnerability-management-standard.md
│   ├── incident-response-plan.md
│   ├── vendor-risk-management-procedure.md
│   ├── data-classification-standard.md
│   └── logging-and-monitoring-standard.md
│
├── 10-audit-readiness/
│   ├── audit-readiness-checklist.md
│   ├── soc2-readiness-checklist.md
│   ├── pci-readiness-checklist.md
│   ├── nist-assessment-readiness.md
│   └── sample-walkthrough-questions.md
│
├── templates/
│   ├── risk-register-template.xlsx
│   ├── control-assessment-template.xlsx
│   ├── evidence-request-template.xlsx
│   ├── poam-template.xlsx
│   ├── executive-summary-template.md
│   ├── policy-template.md
│   └── risk-acceptance-template.md
│
└── references/
    ├── references.md
    └── framework-version-notes.md
```


## Major Deliverables

The main deliverables in this repository include:

| Deliverable | Purpose |
|---|---|
| Client Scenario | Defines the fictional organization, industry, technology environment, and risk drivers. |
| Assessment Scope | Explains what systems, processes, and controls are included in the assessment. |
| Framework Mapping | Shows how controls map across NIST CSF, NIST 800-53, CIS Controls, SOC 2, and PCI DSS. |
| Control Assessment Workbook | Documents control design, operating effectiveness, evidence reviewed, findings, and recommendations. |
| Evidence Request List | Shows the evidence needed to validate controls during a GRC assessment or audit. |
| Risk Register | Identifies enterprise risks, assigns likelihood and impact, and documents treatment plans. |
| Gap Analysis | Compares current-state controls against target-state expectations. |
| POA&M | Tracks weaknesses, remediation actions, owners, due dates, and validation steps. |
| Executive Report | Summarizes risk posture, top findings, business impact, and remediation priorities. |
| Audit Readiness Checklist | Helps prepare the organization for SOC 2, PCI DSS, NIST, or internal audits. |


## Control Domains Covered

This project covers the following control domains:

* Governance and risk management
* Identity and access management
* Privileged access management
* Asset management
* Vulnerability management
* Patch management
* Logging and monitoring
* Incident response
* Vendor risk management
* Data protection
* Encryption
* Backup and recovery
* Business continuity
* Cloud security
* PCI DSS readiness
* SOC 2 readiness
* Audit readiness


## Example Risk Areas

The assessment focuses on realistic enterprise risk areas, including:

* Privileged accounts without MFA
* Critical vulnerabilities not remediated within SLA
* Incomplete vendor risk reviews
* Weak logging and monitoring coverage
* Lack of annual incident response testing
* Incomplete asset inventory
* Poor access review documentation
* Weak PCI segmentation evidence
* Inconsistent data classification practices
* Incomplete disaster recovery testing


## Skills Demonstrated

This repository demonstrates hands-on knowledge of:

* GRC analysis
* Cybersecurity risk assessment
* Control testing
* Framework mapping
* Compliance documentation
* Audit preparation
* Evidence review
* Risk register development
* POA&M creation
* Executive communication
* Policy and procedure writing
* Remediation planning
* Security governance


## Intended Audience

This project is intended for:

* Hiring managers
* GRC managers
* Cybersecurity managers
* Compliance teams
* IT audit teams
* Consulting clients
* Federal and state government contractors
* Banking and fintech organizations
* Technology companies
* Recruiters reviewing GRC portfolio work


## Disclaimer

This is a fictional portfolio project created for demonstration purposes only. The company, risks, control results, findings, and reports are not based on a real client. No confidential, proprietary, or regulated data is included in this repository.
