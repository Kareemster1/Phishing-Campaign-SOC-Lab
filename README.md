# Phishing-Campaign-SOC-Lab

## Overview

This project simulates a SOC investigation into a payroll-themed phishing campaign targeting employees at Cloudora, a fictional HR software company. The goal was to identify the attack, determine its impact, investigate compromised accounts, and document the incident response process.
 
## Key Findings
- 40 employees were targeted by the phishing campaign.
- 6 employees clicked the phishing link.
- 2 employees submitted credentials and had their accounts compromised.
- The attacker successfully accessed both accounts using stolen credentials.
- No evidence of data theft or fraudulent payroll activity was found.
- One reported email was investigated and confirmed to be a legitimate marketing message.

## MITRE ATT&CK Mapping
- **T1566.002** – Phishing: Spearphishing Link
- **T1598.003** – Phishing for Information
- **T1078.004** – Valid Accounts: Cloud Accounts

## Skills Demonstrated
- Phishing Investigation
- Incident Response
- Threat Hunting
- Log Analysis
- IOC Identification
- MITRE ATT&CK Mapping
- Security Reporting
 
## Tools Used
- Exchange Online Message Trace
- Sign-In Logs
- Email Header Analysis
- Microsoft 365 Security Data
- MITRE ATT&CK Framework
 
## Response Actions
- Revoked attacker sessions
- Reset compromised account passwords
- Enforced MFA
- Blocked malicious domains and IPs
- Removed phishing emails from mailboxes
- Verified containment through log analysis
 
## Lessons Learned
This lab reinforced the importance of user awareness, rapid incident response, and MFA enforcement. User-reported phishing emails helped identify the campaign quickly, while log analysis enabled fast containment of compromised accounts.
 
> **Note:** Cloudora is a fictional company and all data used in this project was created for training purposes.
