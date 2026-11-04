# Mapping ISO/IEC 27001:2022 Controls to the Kenya Data Protection Act 2019

I built this crosswalk to understand how an information security management system helps an organisation meet Kenya's data protection law, and where it does not. It maps 46 controls from Annex A of ISO/IEC 27001:2022 to the sections of the Data Protection Act No. 24 of 2019, and lists the parts of the Act that Annex A leaves uncovered.

## Why I made it

Many organisations in Kenya already run security controls, or are working towards ISO 27001, and treat privacy compliance as a separate exercise. In practice the two overlap heavily. Showing the overlap makes it easier to reuse existing evidence, and showing the gaps makes it clear what additional work the Act demands.

## What the workbook contains

| Sheet | Purpose |
|---|---|
| Summary | Counts of controls by link strength and by Annex A theme |
| Control Mapping | Each control, the related sections of the Act, what the Act requires, how the control helps, example audit evidence and the strength of the link |
| Gaps Outside Annex A | 13 areas of the Act with no real Annex A equivalent, and what an organisation needs to do about each |
| Notes | Purpose, method, sources, rating definitions and limits |

## Method

1. I read the Act as published by the Office of the Data Protection Commissioner (ODPC) and noted each duty an organisation must meet.
2. I matched each Annex A control to the sections of the Act it helps to satisfy.
3. I rated each link. **Direct** means the control is expected to implement a stated duty. **Supporting** means it helps indirectly.
4. I listed duties in the Act that no control addresses as gaps.
5. I checked section numbers and headings against the Act text on 3 November 2026.

## What I found

Of the 46 controls, 20 are Direct links and 26 are Supporting links.

- **Where Annex A helps most:** security of personal data (access control, encryption, masking, secure disposal), breach readiness (incident management and event reporting, supporting the 72-hour notification duty in s.43), retention and deletion (ss.39 and 40) and supplier and transfer controls (ss.42, 48 and 49).
- **Where Annex A does not reach:** the rights of data subjects, lawful basis and consent, data protection impact assessments, registration with the Commissioner, the Data Protection Officer appointment, children's data, sensitive personal data, local processing requirements and complaint handling.
- **Practical conclusion:** an ISO 27001 certificate gives a strong base for the security duties in the Act but does not prove compliance with it. ISO/IEC 27701, the privacy extension to ISO 27001, is the natural next step.

## How to use it

- Filter the Control Mapping sheet by Annex A theme or by link strength.
- Use the example evidence column to prepare for an audit or a privacy review.
- Use the Gaps sheet as a starting checklist for work that sits outside an ISO 27001 programme.

## Limits

- I have not mapped the Data Protection (General) Regulations 2021 or the detailed grounds in Part V (ss.44 to 47).
- The ratings are my own judgement and are open to challenge.
- This is a self-study project. It is not legal advice, and no lawyer or auditor has reviewed it.
- ISO standards are copyrighted. I refer to control numbers and names only. Check any control against a licensed copy of the standard.

## Source

The Data Protection Act No. 24 of 2019, Office of the Data Protection Commissioner, https://www.odpc.go.ke/wp-content/uploads/2024/02/TheDataProtectionAct__No24of2019.pdf (read 3 November 2026).

## Author

Benard Emmanuel Kariuki, Nairobi, Kenya.
LinkedIn: linkedin.com/in/emmanuel-benard-kariuki
