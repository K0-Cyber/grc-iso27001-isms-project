# Internal Audit Report

## Audit Details

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| Audit Reference | ISMS Audit 2026-01 |
| Standard | ISO/IEC 27001:2022 |
| Audit Date | January 2026 |
| Auditor | Eugene Amanquah |
| Auditor Independence | Independent from operational functions |
| Scope | All mandatory ISO/IEC 27001:2022 clauses 4–10 and selected Annex A controls |
| Method | Document review, staff interviews, system configuration inspection, and log review |

## Purpose

This simulated internal audit provides evidence of systematic self-assessment against ISO/IEC 27001:2022 requirements.

The purpose of the audit is to evaluate whether the Information Security Management System is appropriately documented and whether identified controls are represented as operating effectively within the simulated organisation.

Internal audit findings are classified as:

| Finding Type | Meaning |
|---|---|
| Major Nonconformity | A significant failure or absence of a key ISMS requirement |
| Minor Nonconformity | A requirement is partially met or inconsistently applied and requires corrective action |
| Observation | An identified weakness or improvement opportunity that does not currently constitute a nonconformity |

## Audit Objectives

The audit assessed:

- Conformance with mandatory ISO/IEC 27001:2022 clauses
- Implementation of selected Annex A controls
- Information security policy and governance
- Risk assessment and treatment
- Asset management
- Supplier security
- Security awareness and training
- Vulnerability management
- ISMS monitoring
- Incident response
- Management review readiness

## Overall Conclusion

The ISMS demonstrates a solid foundation with good implementation of technical controls, particularly in cloud security and identity management.

Key areas requiring attention are:

- Supplier management
- Knowledge and asset management
- Vulnerability scanning programme formalisation
- Security awareness completion
- Formal management review of ISMS KPIs

No Major Nonconformities were identified.

---

# Audit Findings

## F-01 — Supplier Security

| Field | Details |
|---|---|
| Reference | F-01 |
| Clause | A5.19 — Information Security in Supplier Relationships |
| Finding Type | Minor Nonconformity |

### Description

Supplier security questionnaires have been sent, but **3 of 8 suppliers have not returned completed forms**.

Unsigned suppliers currently have access to company systems.

### Evidence Reviewed

- Supplier register
- Email correspondence

### Corrective Action

- Obtain signed supplier security questionnaires within 30 days
- Suspend system access for non-responsive suppliers after 45 days

### Status

Open — corrective action required.

---

## F-02 — Vulnerability Management

| Field | Details |
|---|---|
| Reference | F-02 |
| Clause | A8.8 — Management of Technical Vulnerabilities |
| Finding Type | Minor Nonconformity |

### Description

Vulnerability scanning is performed, but no formal documented process exists for prioritisation or tracking of remediation.

Two Medium vulnerabilities from the most recent scan are not formally tracked.

### Evidence Reviewed

- Vulnerability scan reports
- Patch-management records

### Corrective Action

- Document a formal vulnerability-management procedure
- Create a remediation-tracking register or spreadsheet
- Record vulnerability priority, owner, due date, and status
- Remediate the outstanding vulnerabilities within 30 days

### Status

Open — corrective action required.

---

## F-03 — Security Awareness Training

| Field | Details |
|---|---|
| Reference | F-03 |
| Clause | A6.3 — Information Security Awareness, Education and Training |
| Finding Type | Observation |

### Description

Security awareness training completion is currently **88%**.

Six staff members have not completed annual security awareness training.

No formal escalation process exists for training non-completion.

### Evidence Reviewed

- Training records
- HR system

### Corrective Action

- Establish escalation to line managers where training remains incomplete after 14 days
- Achieve 100% training completion by the end of Q1

### Status

Improvement action identified.

---

## F-04 — ISMS Monitoring

| Field | Details |
|---|---|
| Reference | F-04 |
| Clause | 9.1 — Monitoring, Measurement, Analysis and Evaluation |
| Finding Type | Observation |

### Description

ISMS performance KPIs have been defined but have not been formally reviewed at management level since implementation.

Management review has not yet been scheduled.

### Evidence Reviewed

- ISMS KPI documentation
- Management calendar

### Corrective Action

- Schedule the first formal management review for February 2026
- Establish a quarterly management-review cadence going forward

### Status

Improvement action identified.

---

## F-05 — Asset Inventory

| Field | Details |
|---|---|
| Reference | F-05 |
| Clause | A5.9 — Inventory of Information and Other Associated Assets |
| Finding Type | Observation |

### Description

The asset register accurately records primary information assets, but personal devices used by **4 contractors** to access company email are not registered.

### Evidence Reviewed

- Asset register
- Contractor access logs

### Corrective Action

- Add the four contractor devices to the asset register
- Update contractor agreements to require MDM enrolment for devices accessing company information

### Status

Improvement action identified.

---

# Findings Summary

| Finding Type | Count |
|---|---:|
| Major Nonconformity | 0 |
| Minor Nonconformity | 2 |
| Observation | 3 |
| **Total** | **5** |

## Corrective Action Summary

| Ref | Area | Required Action | Priority |
|---|---|---|---|
| F-01 | Supplier Security | Complete supplier questionnaires and restrict access where required | High |
| F-02 | Vulnerability Management | Formalise vulnerability-management and remediation tracking | High |
| F-03 | Training | Raise security-awareness completion from 88% to 100% | Medium |
| F-04 | Monitoring | Establish formal management review of ISMS KPIs | Medium |
| F-05 | Asset Management | Register contractor devices and enforce MDM requirements | Medium |

## Links to Other ISMS Documents

Audit findings should feed into:

- Risk Register
- Risk Treatment Plan
- Statement of Applicability
- Asset Inventory
- Supplier Security Policy
- Management Review Minutes
- Continual improvement activities

## Evidence Note

This is a simulated portfolio internal audit.

Some of the source project's technical-control evidence is intended to be supported by separate hands-on technical labs. Where those labs have not yet been completed, this repository should not be interpreted as independent evidence that those technical configurations have already been deployed in a production environment.

The future `10-evidence/` folder will contain supporting technical evidence as those labs are completed.

## Audit Conclusion

The simulated EugTech ISMS demonstrates a structured ISO/IEC 27001:2022 implementation with no Major Nonconformities identified.

The two Minor Nonconformities require corrective action in:

1. Supplier security assurance
2. Vulnerability-management formalisation

The three Observations identify opportunities to strengthen:

1. Security-awareness completion
2. Management review
3. Asset inventory completeness

Progress against these findings should be reviewed during the February 2026 management review.

## Status

Status: Simulated Internal Audit Completed  
ISO 27001 Mapping: Clause 9.2  
Findings: 5 — 2 Minor Nonconformities, 3 Observations  
Project: ISO/IEC 27001:2022 GRC & ISMS Implementation Project
