# SOC 2 and ISO 27001:2022 Control Crosswalk

This page lists the controls I have checked so far against the AICPA Trust Services Criteria and ISO/IEC 27001:2022 Annex A: 7 of 16 as of 14 October 2026. The remaining controls are in the Excel workbook in this folder, marked as pending review, and I will add them here as I check them.

Each control has one plain language statement, mapped to both frameworks. The workbook also holds the evidence and risk columns for every row, the readiness checklist, and the notes on sources and limits.

## Summary

| ID | Control topic | SOC 2 criteria | ISO 27001:2022 reference | Verified |
|---|---|---|---|---|
| C01 | Policies and responsibilities | CC1.3, CC2.2, CC5.3 | A.5.1, A.5.2 | B.K 14/10/2026 |
| C02 | Risk assessment | CC3.1, CC3.2 | Clauses 6.1.2 and 8.2 (main body) | B.K 14/10/2026 |
| C04 | Periodic access review | CC6.1, CC6.3 | A.5.18 | B.K 14/10/2026 |
| C06 | Encryption | CC6.1, CC6.7 | A.8.24 | B.K 14/10/2026 |
| C12 | Change management | CC8.1 | A.8.32 | B.K 14/10/2026 |
| C13 | Vendor management | CC9.2 | A.5.19, A.5.20, A.5.22, A.5.23 | B.K 14/10/2026 |
| C14 | Backup, recovery and continuity | A1.2, A1.3, CC9.1 | A.8.13, A.5.29, A.5.30 | B.K 14/10/2026 |

## Control details

### C01 Policies and responsibilities

- SOC 2 criteria: CC1.3, CC2.2, CC5.3
- ISO 27001:2022 reference: A.5.1, A.5.2
- Control statement: Information security policies are approved by management, reviewed on a set schedule, and communicated to staff. Security roles and responsibilities are assigned in writing.
- Evidence an auditor would request: Approved policy with version number and date; staff acknowledgement records; organization chart or responsibility matrix.
- Risk if the control fails: Controls have no owner, policies go stale, and staff cannot be held to rules they never received.
- Verified: B.K 14/10/2026

### C02 Risk assessment

- SOC 2 criteria: CC3.1, CC3.2
- ISO 27001:2022 reference: Clauses 6.1.2 and 8.2 (main body)
- Control statement: Risks are identified, scored and recorded in a risk register that is reviewed at least annually and after major changes.
- Evidence an auditor would request: Risk register with owners and dates; risk assessment methodology; minutes of the review meeting.
- Risk if the control fails: Exposures stay unknown, so money and effort go to the wrong controls.
- Verified: B.K 14/10/2026

### C04 Periodic access review

- SOC 2 criteria: CC6.1, CC6.3
- ISO 27001:2022 reference: A.5.18
- Control statement: User access to production systems is reviewed every quarter by the system owner, and any unneeded access is removed.
- Evidence an auditor would request: Signed and dated review log; list of users reviewed; tickets showing removals made after the review.
- Risk if the control fails: Excess or stale access accumulates and unauthorized access goes unnoticed.
- Verified: B.K 14/10/2026

### C06 Encryption

- SOC 2 criteria: CC6.1, CC6.7
- ISO 27001:2022 reference: A.8.24
- Control statement: Sensitive data is encrypted at rest and in transit using approved methods, and encryption keys are managed and protected.
- Evidence an auditor would request: Encryption settings for databases and storage; TLS configuration scan; key management procedure.
- Risk if the control fails: Data is readable if a device, backup or network connection is compromised.
- Verified: B.K 14/10/2026

### C12 Change management

- SOC 2 criteria: CC8.1
- ISO 27001:2022 reference: A.8.32
- Control statement: Changes to systems are requested, reviewed, tested and approved before release, and the person who approves is not the person who makes the change.
- Evidence an auditor would request: Change tickets with approval and test evidence; code review records; emergency change procedure.
- Risk if the control fails: Untested or unauthorized changes break systems or introduce weaknesses.
- Verified: B.K 14/10/2026

### C13 Vendor management

- SOC 2 criteria: CC9.2
- ISO 27001:2022 reference: A.5.19, A.5.20, A.5.22, A.5.23
- Control statement: Vendors with access to company data or systems are assessed before onboarding, covered by security terms in the contract, and reviewed on a schedule.
- Evidence an auditor would request: Vendor list with risk rating; completed assessments or vendor audit reports; contracts with security clauses.
- Risk if the control fails: A weakness at a supplier becomes a breach of your own data.
- Verified: B.K 14/10/2026

### C14 Backup, recovery and continuity

- SOC 2 criteria: A1.2, A1.3, CC9.1
- ISO 27001:2022 reference: A.8.13, A.5.29, A.5.30
- Control statement: Backups are taken on a schedule, protected, and restored in tests. A continuity and recovery plan covers critical systems with defined recovery targets.
- Evidence an auditor would request: Backup job logs; restore test record; continuity plan with recovery time targets.
- Risk if the control fails: A failure or attack causes data loss or long outages with no tested way back.
- Verified: B.K 14/10/2026

## Sources

- AICPA, Trust Services Criteria for Security, Availability, Processing Integrity, Confidentiality, and Privacy (2017, with revised points of focus 2022)
- ISO/IEC 27001:2022, Information security management systems, Annex A

The README lists the secondary cross-check used and the limits of this review.
