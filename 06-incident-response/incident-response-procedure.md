# Incident Response Procedure

## Purpose

This document defines the incident response process for EugTech Solutions Ltd.

It supports ISO/IEC 27001:2022 Annex A control **A5.24 — Information Security Incident Management Planning and Preparation**.

The procedure ensures that security incidents are identified, contained, eradicated, recovered from, and reviewed in a consistent and documented manner.

## Scope

This procedure applies to:

- Employees
- Contractors
- Information systems
- Cloud infrastructure
- Client data
- End-user devices
- Microsoft 365
- Azure and AWS environments
- Source code repositories
- Third-party services within the ISMS scope

## Incident Classification

| Severity | Definition | Response Requirement |
|---|---|---|
| P1 — Critical | Active data breach, ransomware, or confirmed system compromise | Response within 1 hour. ISM and CEO notified immediately. ICO notification may be required within 72 hours |
| P2 — High | Suspected breach, significant service disruption, or malware detected | Response within 4 hours. ISM notified within 30 minutes |
| P3 — Medium | Policy violation, phishing email opened, or unauthorised access attempt | Response within 24 hours. ISM notified the same business day |
| P4 — Low | Minor policy breach, lost company property containing no sensitive data, or suspicious email reported | Response within 72 hours. Incident logged and reviewed |

## Incident Reporting

Any staff member who suspects an information security incident must report it immediately.

Incidents may be reported through:

- Email to `security@eugtech.co.uk`
- Direct contact with the Information Security Manager
- Security monitoring alerts
- Microsoft Sentinel
- Microsoft Defender for Cloud
- User or client reports

## Incident Response Lifecycle

The incident response process follows five phases:

```text
IDENTIFY
   ↓
CONTAIN
   ↓
ERADICATE
   ↓
RECOVER
   ↓
LEARN
```

## Phase 1 — Identify

Any employee or contractor who suspects a security incident must report it immediately.

The Information Security Manager will:

- Review the initial report
- Gather available evidence
- Assign an initial incident classification
- Record the incident
- Determine whether immediate escalation is required

Sentinel and Defender for Cloud alerts are triaged by the Information Security Manager.

Initial classification should be assigned within 30 minutes where possible.

## Phase 2 — Contain

Immediate actions must be taken to limit further damage.

Containment actions may include:

- Disable compromised Entra ID accounts
- Isolate affected virtual machines
- Modify Network Security Group rules
- Revoke compromised credentials
- Rotate secrets through Azure Key Vault
- Block malicious IP addresses or accounts
- Preserve logs and forensic evidence
- Restrict affected services

Systems must not be wiped or rebuilt before relevant forensic evidence has been preserved.

## Phase 3 — Eradicate

The root cause of the incident must be removed.

Actions may include:

- Patch identified vulnerabilities
- Remove malware
- Close attack vectors
- Reset compromised passwords
- Rotate credentials
- Remove malicious accounts or persistence mechanisms
- Correct insecure configurations

Eradication should be confirmed using available security monitoring tools before recovery begins.

## Phase 4 — Recover

Affected systems and services should be restored safely.

Recovery activities may include:

- Restore systems from clean Azure Backup copies
- Re-enable affected services gradually
- Apply increased monitoring
- Validate that systems operate normally
- Confirm compromised credentials are no longer valid
- Notify affected clients where required

Where personal data is involved, EugTech must assess whether notification to the Information Commissioner's Office is required.

Where UK GDPR notification is required, the ICO must be notified within 72 hours of becoming aware of the personal data breach.

## Phase 5 — Learn

A post-incident review must be completed within five business days.

The review should document:

- Incident timeline
- Root cause
- Impact
- Controls that worked effectively
- Controls that failed or were missing
- Lessons learned
- Corrective actions

Following the review:

- Update the Risk Register where a new or changed risk is identified
- Update the Statement of Applicability where control gaps are identified
- Update security procedures where required
- Share relevant lessons with staff
- Include significant incidents in management review

## Incident Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Information Security Manager | Coordinates incident response, classification, escalation, evidence preservation, and post-incident review |
| CEO | Receives immediate notification for Critical incidents and supports major business decisions |
| IT Manager | Supports technical containment, recovery, account management, and infrastructure actions |
| Data Protection Officer / Privacy Lead | Assesses personal data breach implications and regulatory notification requirements |
| System Owners | Support investigation and restoration of affected services |
| All Staff | Immediately report suspected security incidents |

## Evidence Preservation

Relevant evidence may include:

- Microsoft Sentinel logs
- Defender for Cloud alerts
- Entra ID sign-in logs
- Azure activity logs
- AWS CloudTrail logs
- Endpoint logs
- Email headers
- Screenshots
- Configuration exports
- Incident communications

Evidence must be preserved before destructive remediation where practical.

## GDPR Notification Assessment

A personal data incident requires an assessment of whether notification under UK GDPR is necessary.

Where the breach is likely to result in a risk to individuals' rights and freedoms, EugTech must notify the ICO within 72 hours of becoming aware of the breach.

The notification should include:

- Nature of the breach
- Categories of affected data
- Approximate number of affected individuals
- Likely consequences
- Measures taken or proposed

## Incident Records

Each incident record should contain:

- Incident ID
- Date and time
- Detection method
- Severity
- Systems or information affected
- Description
- Containment actions
- Root cause
- Recovery actions
- Regulatory assessment
- Corrective actions
- Closure date
- Lessons learned

## Review

This procedure should be reviewed:

- Annually
- Following a significant incident
- After major changes to systems or infrastructure
- Following internal audit findings
- Following changes to legal or regulatory requirements

## Status

Status: Implemented  
ISO 27001 Mapping: Annex A A5.24  
Project: ISO/IEC 27001:2022 GRC & ISMS Implementation Project
