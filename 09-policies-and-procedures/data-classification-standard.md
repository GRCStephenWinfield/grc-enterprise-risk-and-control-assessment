# Data Classification Standard

## Purpose

The purpose of this Data Classification Standard is to define how BayouTrust Digital Bank classifies, handles, stores, transmits, and protects information based on sensitivity and business value.

This standard supports the protection of customer data, financial records, payment card data, employee records, vendor information, and internal business information.

## Scope

This standard applies to:

- Employees
- Contractors
- Vendors
- Business systems
- Cloud environments
- Banking applications
- Payment systems
- Customer databases
- Internal documents
- Reports and exports
- Email and file sharing platforms

## Data Classification Objectives

The objectives of data classification are to:

- Identify sensitive data.
- Apply appropriate protection based on risk.
- Reduce unauthorized access to sensitive information.
- Support regulatory and compliance requirements.
- Improve data handling consistency.
- Support audit readiness.
- Reduce the risk of data exposure.

## Data Classification Levels

| Classification | Description | Examples |
|---|---|---|
| Public | Information approved for public release. | Public website content, press releases, marketing materials. |
| Internal | Information intended for internal business use only. | Internal procedures, meeting notes, general business documents. |
| Confidential | Sensitive business or customer information that requires protection. | Customer records, employee records, vendor contracts, internal financial reports. |
| Restricted | Highly sensitive information requiring the strongest protection. | Payment card data, authentication secrets, encryption keys, privileged access records, regulated financial data. |

## Data Handling Requirements

| Classification | Access | Storage | Transmission | Sharing |
|---|---|---|---|---|
| Public | Available to public users. | Approved public systems. | No special protection required. | May be shared externally after approval. |
| Internal | Employees and authorized contractors. | Approved internal systems. | Company-approved communication tools. | Internal sharing only. |
| Confidential | Authorized users with business need. | Approved systems with access controls. | Encrypted where appropriate. | Limited to approved users and vendors. |
| Restricted | Strictly limited authorized users. | Secure systems with strong access controls and monitoring. | Encryption required. | Sharing requires documented approval. |

## Classification Requirements

### 1. Data Owners

Data owners are responsible for determining the appropriate classification of data.

Data owners should consider:

- Sensitivity
- Regulatory requirements
- Business impact
- Customer impact
- Legal impact
- Contractual requirements
- Risk of unauthorized disclosure

### 2. Access Control

Access to Confidential and Restricted data must be limited based on business need and least privilege.

Access should be reviewed on a regular basis.

### 3. Encryption

Confidential and Restricted data should be encrypted where appropriate.

Restricted data must be encrypted when stored or transmitted unless an approved exception exists.

### 4. Data Transmission

Sensitive data should only be transmitted using approved secure methods.

Restricted data should not be sent through unsecured email or unapproved file sharing services.

### 5. Data Storage

Sensitive data must be stored only in approved locations.

Users should not store Confidential or Restricted data on personal devices or unapproved systems.

### 6. Data Retention

Data must be retained according to business, legal, regulatory, and record retention requirements.

Data that is no longer needed should be securely deleted according to approved procedures.

### 7. Data Sharing

Sensitive data may only be shared with authorized users or approved vendors.

Vendor sharing must follow vendor risk management and contractual requirements.

## Examples of Restricted Data

Restricted data may include:

- Payment card data
- Customer account numbers
- Authentication credentials
- Encryption keys
- Security tokens
- Privileged access records
- Non-public financial information
- Sensitive regulatory reports
- Security incident details

## Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Data Owners | Classify data and approve access. |
| Users | Handle data according to classification requirements. |
| Managers | Ensure team members follow data handling procedures. |
| Security Team | Define technical safeguards for sensitive data. |
| GRC Team | Review data protection controls and evidence. |
| Legal and Compliance | Advise on legal, regulatory, and contractual requirements. |
| Vendor Risk Team | Review third-party access to sensitive data. |

## Exceptions

Exceptions to this standard must be documented and approved.

Exception requests should include:

- Data type
- Classification level
- Business justification
- Risk rating
- Compensating controls
- Approval owner
- Expiration date

## Compliance Mapping

This standard supports requirements from:

- NIST Cybersecurity Framework
- NIST SP 800-53
- CIS Controls
- SOC 2 Trust Services Criteria
- PCI DSS

## Review Frequency

This standard should be reviewed at least annually or when significant changes occur to business processes, regulatory requirements, technology systems, or data handling practices.

## Summary

Data classification helps the organization understand what data it has, how sensitive it is, who should access it, and how it should be protected.

A consistent data classification process supports cybersecurity, privacy, compliance, and audit readiness.
