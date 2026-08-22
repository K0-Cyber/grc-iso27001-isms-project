# Risk Register

## Purpose

This document records the information security risks identified for EugTech Solutions Ltd.

It supports ISO/IEC 27001:2022 Clause 6.1.2.

## Risk Register — EugTech Solutions Ltd

| Risk ID | Asset | Threat | Likelihood | Impact | Source Risk Rating | Residual Risk | Status |
|---|---|---|---:|---:|---|---|---|
| R-001 | Client data in Azure | Unauthorised access via misconfigured IAM | 3 | 5 | HIGH: 15 | MED: 9 | In Progress |
| R-002 | Staff laptops | Device theft or loss exposing client data | 3 | 4 | HIGH: 12 | LOW: 4 | Implemented |
| R-003 | Source code repository | Hardcoded credentials committed to GitHub | 2 | 5 | HIGH: 10 | MED: 6 | In Progress |
| R-004 | Supplier access | Third-party vendor with excessive access to systems | 2 | 4 | MED: 8 | LOW: 4 | Implemented |
| R-005 | Staff | Phishing attack leading to credential compromise | 4 | 4 | HIGH: 16 | MED: 8 | In Progress |
| R-006 | Cloud infrastructure | Ransomware encrypting client data backups | 2 | 5 | HIGH: 10 | LOW: 5 | Implemented |
| R-007 | Network | Man-in-the-middle attack on remote worker connections | 2 | 3 | MED: 6 | LOW: 3 | Implemented |
| R-008 | Microsoft 365 | Business email compromise (BEC) | 3 | 4 | HIGH: 12 | MED: 6 | Implemented |
| R-009 | Client data | Data retention — holding data beyond agreed period | 2 | 4 | MED: 8 | LOW: 4 | In Progress |
| R-010 | Key personnel | Knowledge loss if key staff depart suddenly | 3 | 3 | MED: 9 | MED: 6 | Open |

## Register Summary

The Risk Register contains 10 information security risks covering:

- Cloud access control
- Endpoint security
- Secrets management
- Supplier access
- Phishing
- Ransomware
- Remote-working network security
- Business email compromise
- Data retention
- Key-person dependency

## Treatment Link

Risks requiring specific treatment actions are linked to the Risk Treatment Plan.

The Risk Treatment Plan currently documents treatment activities for:

- R-001
- R-002
- R-003
- R-005
- R-008
- R-010

## Source Classification Note

The risk labels above reproduce the classifications used in the original project document.

The source methodology separately defines:

- Low: 1–8
- Medium: 9–15
- High: 16–25

Some labels in the original Risk Register do not align with those numerical thresholds. They have been retained here to preserve the source project data pending a formal risk-register review.

## Review Requirements

The Risk Register should be reviewed:

- At least annually
- Following significant change
- Following a major security incident
- When new threats or vulnerabilities arise
- When treatment actions materially change residual risk

## Status

Status: Implemented  
ISO 27001 Mapping: Clause 6.1.2  
Project: ISO/IEC 27001:2022 GRC & ISMS Implementation Project
