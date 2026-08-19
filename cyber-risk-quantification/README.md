# Cyber Risk Quantification — FAIR Risk Register

**File:** [FAIR_Risk_Register.xlsx](./FAIR_Risk_Register.xlsx)
**Related writing:** [Why I Think Every CISO Needs to Start Speaking in Dollars, Not Adjectives](https://medium.com/@emanukariuki/why-i-think-every-ciso-needs-to-start-speaking-in-dollars-not-adjectives-a1adf9337eb9)

## Overview

This workbook applies the FAIR (Factor Analysis of Information Risk) model to estimate Annualized Loss Expectancy (ALE) for a hypothetical mid-size Kenyan fintech. It translates public breach-cost benchmarks into scenario-level financial exposure and treatment priorities, extending the CRQ methodology from the companion Medium article.

## What's inside

- **Legend tab** — purpose, usage instructions, and color-coding key
- **FAIR Assumptions tab** — Loss Event Frequency (LEF) scale and loss magnitude anchor points, each sourced (primarily IBM's Cost of a Data Breach Report 2025), plus a documented 12% regional scaling factor applied to adapt global/US figures to an East African fintech's size
- **Risk Register tab** — 10 scenarios (ransomware, third-party/supply chain breach, insider exfiltration, phishing account takeover, cloud misconfiguration, DDoS, unpatched web app RCE/SQLi, API IDOR, ODPC/DPIA non-compliance, shadow AI) each with LEF, loss magnitude, calculated ALE, likelihood/impact category, existing controls, treatment recommendation, and risk owner
- **Heat Map tab** — one-page Likelihood x Impact summary across all 10 scenarios

## Key result

Portfolio Total ALE across the 10 scenarios: **$1,257,596**. The highest single exposure is a cloud storage misconfiguration scenario (Critical rating, $266,400 ALE), reflecting both a plausible likelihood and financial-services-scale loss magnitude.

## Methodology notes

- Magnitude anchors are drawn from named, dated public sources (cited on the FAIR Assumptions tab) rather than invented figures.
- One scenario (API IDOR) is modeled directly on a finding pattern from the Vulnbank penetration test in this portfolio, showing how a technical finding can feed a quantitative risk register.
- The regional scaling factor is flagged explicitly as an analyst assumption, not a sourced figure, so it's transparent to any reviewer.
