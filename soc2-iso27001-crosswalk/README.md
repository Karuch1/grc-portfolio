# SOC 2 and ISO 27001 Crosswalk

I built this crosswalk to show how one security control can satisfy both SOC 2 and ISO 27001:2022. A company pursuing both frameworks does not need two sets of controls. It needs one control, mapped to both, with one body of evidence.

## What is in this folder

| File | Purpose |
|---|---|
| SOC2_ISO27001_Crosswalk.xlsx | Full workbook with three tabs: Crosswalk, Checklist, and Notes and Sources |
| crosswalk.md | Readable version of the crosswalk table |

## What the workbook covers

16 control areas: policies and responsibilities, risk assessment, access provisioning, periodic access review, privileged access and authentication, encryption, network protection, malware protection, vulnerability management, logging and monitoring, incident response, change management, vendor management, backup and continuity, security awareness training, and physical security.

For each area I give the SOC 2 criteria, the ISO 27001:2022 reference, a plain language control statement, the evidence an auditor would request, and the risk if the control fails. The Checklist tab turns the same controls into a readiness check with a status dropdown and a live summary.

## Worked example

Control: user access to production systems is reviewed every quarter by the system owner, and unneeded access is removed.

- SOC 2: CC6.1, CC6.3
- ISO 27001:2022: A.5.18
- Evidence: signed and dated review log, list of users reviewed, tickets showing removals
- Risk if it fails: excess or stale access builds up and unauthorized access goes unnoticed

## Status and limits

The mappings are a study aid. Rows with my initials and a date in the verified column of the Crosswalk tab have been checked against the AICPA Trust Services Criteria and ISO/IEC 27001:2022 Annex A. The remaining rows are pending review. I started with the seven rows I was least sure of: C01, C02, C06, C11, C12, C13 and C14. Mappings differ between practitioners, so treat each row as a reasoned starting point and not an official equivalence.

The Checklist tab is a template. Statuses are left as Not assessed on purpose, because the sheet shows how the criteria map and is not an assessment of a real company.

## Revision notes

14 October 2026, first review pass:

- C01: added CC2.2 for communication of policies to staff.
- C06: reworded the note so that CC6.1 and CC6.7 are both described as addressing encryption.
- C11: added A.5.28 (Collection of evidence).
- C12: removed A.8.9, since A.8.32 is the direct match for change management.
- C13: added A.5.23 (Information security for use of cloud services).

## Sources

- AICPA, Trust Services Criteria for Security, Availability, Processing Integrity, Confidentiality, and Privacy (2017, with revised points of focus 2022)
- ISO/IEC 27001:2022, Information security management systems, Annex A

Secondary cross-check, not an authority:

- Axipro (Pedro Dias), "SOC 2 to ISO 27001 Mapping: A Crosswalk Guide", published 19 May 2026, last updated 20 May 2026, https://axipro.co/soc-2-to-iso-27001-mapping/, accessed 14 October 2026.

Last updated: 14 October 2026
