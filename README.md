# Coincheck 2018 Cryptocurrency Exchange Hack — Forensic Investigation

## Overview
An independent cybersecurity research report investigating the January 2018 
Coincheck hack — one of the largest cryptocurrency thefts in history (~$530M 
in NEM stolen). This case study covers forensic analysis, attack vectors, 
blockchain tracing, and security recommendations.

**Author:** Vignesh S | Independent Cybersecurity Researcher | First Quadrant Labs

## Key Facts
- Date: January 26, 2018
- Loss: 523 million NEM (XEM) ≈ $530 million USD
- Victims: 260,000+ Coincheck customers
- Root Cause: Hot wallet storage + no multi-signature security

## What This Report Covers
- Full incident timeline (breach to regulatory action)
- Attack vector identification (phishing → RAT → hot wallet access)
- Blockchain forensics using NEM Explorer & OSINT
- Vulnerability assessment table
- Executive-level mitigation plan (0–30 days, 1–6 months, 6–12 months)
- Forensic evidence portfolio (A1–A8)

## Tools & Methods Used
- NEM Blockchain Explorer (transaction tracing)
- OSINT Framework (open-source intelligence)
- Graph-based transaction analysis (fund flow visualization)
- Timeline reconstruction from public disclosures

## Key Findings
- Private keys stored on unencrypted internet-connected Windows desktop
- No multi-signature authorization on hot wallet
- No real-time anomaly detection — theft went undetected for hours
- Funds laundered via darknet at 15% discount, split across multiple wallets

## Outcome
- FSA issued business improvement order to Coincheck
- Coincheck acquired by Monex Group (April 2018)
- 31 individuals arrested (2021) for laundering stolen NEM
- Majority of funds never recovered

## Files
- `Coincheck_Hack_Investigation_Report.pdf` — Full forensic report

## References
- NEM Blockchain Explorer
- Japan Financial Services Agency (FSA) Reports
- Reuters, Nikkei Asia, Japan Times
- Chainalysis Industry Report (2019)
