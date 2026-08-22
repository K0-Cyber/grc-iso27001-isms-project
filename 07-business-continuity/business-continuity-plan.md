# Business Continuity Plan

## Purpose

This document defines the approach used by EugTech Solutions Ltd to maintain information security and essential business operations during disruption.

It supports ISO/IEC 27001:2022 Annex A control **A5.29 — Information Security During Disruption**.

## Organisation

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| Sector | Technology — Cloud Consultancy and Managed Services |
| Employees | 50 |
| Key Platforms | Azure, AWS, Microsoft 365, GitHub, corporate endpoints |
| BCP Owner | Information Security Manager |
| Review Frequency | Annual and after significant disruption |
| ISO 27001 Mapping | Annex A A5.29 |

## Scope

The Business Continuity Plan applies to services and systems within the ISMS scope, including:

- Cloud consultancy services
- Managed IT services
- Azure infrastructure
- AWS infrastructure
- Microsoft 365
- Source code repositories
- Staff endpoints
- Remote-working services
- Client information
- Supporting internal IT systems

## Business Continuity Objectives

The objectives of this plan are to:

- Maintain critical services during disruption where possible
- Protect the confidentiality, integrity, and availability of information
- Restore affected systems in a controlled manner
- Minimise disruption to client services
- Maintain communication with staff and clients
- Preserve security controls during recovery
- Ensure incidents and lessons learned feed into continual improvement

## Potential Disruption Scenarios

The plan considers disruption caused by:

- Cloud service outage
- Microsoft 365 outage
- Ransomware
- Loss of access to corporate premises
- Staff device loss or failure
- Network or VPN outage
- Supplier service failure
- Loss of critical personnel
- Significant cybersecurity incident
- Data corruption or loss

## Recovery Priorities

Recovery priorities should consider:

1. Safety of staff and affected individuals
2. Protection of client and company information
3. Restoration of identity and access services
4. Restoration of client-facing services
5. Restoration of communication systems
6. Restoration of internal business systems
7. Recovery of lower-priority supporting services

## Recovery Time and Recovery Point Objectives

The source project specifies that **RTO and RPO should be defined per service**, but does not provide numerical targets.

The following table is therefore maintained as the working BCP register until service-specific targets are formally approved.

| Service | Business Criticality | RTO | RPO | Recovery Method |
|---|---|---|---|---|
| Azure client services | High | To be defined | To be defined | Azure recovery procedures and backups |
| AWS client services | High | To be defined | To be defined | AWS service recovery and backup procedures |
| Microsoft 365 | High | To be defined | To be defined | Microsoft cloud service recovery and continuity arrangements |
| GitHub repositories | High | To be defined | To be defined | Repository recovery and version-control history |
| Staff endpoints | Medium | To be defined | To be defined | Replacement device, MDM enrolment, restored business data |
| VPN infrastructure | High | To be defined | To be defined | Restore or rebuild secure remote-access service |
| Internal business systems | Medium | To be defined | To be defined | Restore from approved backups |

### Definitions

**Recovery Time Objective (RTO)**  
The maximum acceptable time that a service can remain unavailable following disruption.

**Recovery Point Objective (RPO)**  
The maximum acceptable amount of data loss measured in time.

Service owners must formally approve RTO and RPO targets based on business impact and client requirements.

## Backup and Recovery

The project uses backup controls to support availability and recovery.

The Statement of Applicability records:

- Automated daily backups using Azure Backup
- Weekly full backups
- Daily incremental backups
- Quarterly restore testing

Recovery must use validated clean backup copies where compromise is suspected.

## Business Continuity Response

### 1. Assess

The Information Security Manager and relevant service owner assess:

- Nature of the disruption
- Services affected
- Expected duration
- Information security impact
- Client impact
- Whether incident response procedures must also be activated

### 2. Activate

The BCP should be activated where disruption materially affects the organisation's ability to deliver critical services.

Relevant staff and management should be notified.

### 3. Maintain Security

Information security controls must continue during disruption.

Temporary recovery arrangements must not bypass:

- Access control
- Authentication
- Encryption
- Logging
- Data protection
- Least-privilege requirements

Any emergency access granted during recovery must be documented and reviewed after normal operations resume.

### 4. Recover

Recovery activities may include:

- Restore affected systems from clean backups
- Rebuild infrastructure
- Restore secure remote access
- Replace failed staff devices
- Redirect staff to alternative working arrangements
- Recover cloud services
- Restore business communications
- Validate security controls before returning services to normal operation

### 5. Resume

Services should return to normal operation only after:

- Core functionality has been validated
- Information integrity has been checked
- Security controls are confirmed operational
- Service owners approve restoration

## Remote Working Continuity

EugTech operates with both London-based and remote UK staff.

Where physical office access is unavailable, authorised staff may continue operations remotely subject to the Remote Working Policy.

Remote operations must continue to use:

- Approved VPN
- Company-managed devices
- Device encryption
- MFA
- MDM
- Approved communication platforms

## Key-Person Dependency

Risk R-010 identifies knowledge loss caused by sudden departure of key personnel.

The Risk Treatment Plan requires:

- Documentation of critical processes
- Identification of backup personnel
- Cross-training
- Knowledge-base maintenance

These activities also support business continuity.

## Roles and Responsibilities

| Role | Responsibility |
|---|---|
| CEO | Executive decision-making and resource approval during significant disruption |
| Information Security Manager | Coordinates continuity response and information security considerations |
| IT Manager | Restores infrastructure, endpoints, communications, and access services |
| Service Owners | Prioritise and validate restoration of their services |
| Department Heads | Coordinate staff and operational workarounds |
| All Staff | Follow continuity instructions and report disruption or security concerns |

## Communication

During significant disruption, communications should include where relevant:

- Senior management
- Employees
- Affected clients
- Suppliers
- Service providers
- Regulators where notification obligations apply

Communications must be accurate and approved before external distribution.

## Testing

The source project specifies **annual BCP testing**.

Testing should assess:

- Recovery procedures
- Staff responsibilities
- Backup restoration
- Remote-working capability
- Communications
- Security controls during disruption

Evidence should include:

- Test date
- Scenario
- Participants
- Results
- Problems identified
- Corrective actions
- Retest status

## BCP Test Register

| Test Date | Scenario | Result | Findings | Corrective Action |
|---|---|---|---|---|
| To be scheduled | Annual continuity exercise | Pending | Pending | Pending |

## Post-Disruption Review

After a significant disruption or continuity test:

- Document lessons learned
- Review RTO and RPO assumptions
- Update recovery procedures
- Update the Risk Register where required
- Update the Statement of Applicability if controls change
- Track corrective actions
- Include significant findings in management review

## Review Requirements

This plan should be reviewed:

- Annually
- Following a significant disruption
- Following a continuity test
- After major infrastructure changes
- After material supplier changes
- Following relevant internal audit findings

## Current Implementation Status

The project source records A5.29 as **Partially Implemented**.

The BCP is documented, but further maturity requires:

- Formal approval of service-specific RTO values
- Formal approval of service-specific RPO values
- Completion and evidence of annual continuity testing

## Status

Status: Partially Implemented  
ISO 27001 Mapping: Annex A A5.29  
Project: ISO/IEC 27001:2022 GRC & ISMS Implementation Project
