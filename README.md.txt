# Endpoint Security Posture Monitoring Using Splunk

## Project Overview
This project focuses on analysing endpoint security posture using Splunk Enterprise. A CSV dataset containing endpoint security information was imported into Splunk and investigated using Search Processing Language (SPL).

The objective was to identify endpoint security weaknesses, analyse security-control configurations and create a dashboard to visualise the findings.

## Objectives
- Import and analyse endpoint security data using Splunk.
- Monitor endpoint health status.
- Identify devices with Tamper Protection disabled.
- Review available disk-encryption information.
- Analyse antivirus protection distribution.
- Identify endpoints requiring further security investigation.
- Build an endpoint security monitoring dashboard.

## Tools and Technologies
- Splunk Enterprise
- Search Processing Language (SPL)
- CSV Dataset
- Windows Endpoint Security Concepts
- GitHub

## Investigation Summary

| Investigation | Result |
|---|---:|
| Total endpoints | 7 |
| Healthy endpoints | 6 |
| Critical endpoints | 1 |
| Tamper Protection Off | 3 |
| Tamper Protection On | 4 |
| Encryption Enabled | 1 |
| Encryption Not Reported | 6 |
| Endpoints Requiring Review | 6 |

## Key Findings
1. One endpoint was classified as Critical in the dataset.
2. Three endpoints had Tamper Protection disabled.
3. Six endpoints had no reported encryption status.
4. Antivirus protection products were recorded across all seven endpoints.
5. Six endpoints were flagged for further review based on the investigation rules.

## Splunk Dashboard
The dashboard includes:
- Endpoint Health Status
- Tamper Protection Status
- Endpoint Security Inventory
- Endpoint Encryption Status
- Antivirus Protection Distribution
- Endpoint Last Active Overview
- Combined Endpoint Risk Assessment
- Overall Endpoint Risk Summary

## Recommendations
- Investigate endpoints with Critical health status.
- Review and enable Tamper Protection where appropriate.
- Verify missing disk-encryption information.
- Review endpoint protection configurations.
- Regularly monitor endpoint security health.

## Conclusion
This project provided practical experience in importing endpoint security data into Splunk, writing SPL queries, analysing security configurations and creating a monitoring dashboard.

It demonstrates beginner-level SOC analysis skills, including data investigation, identifying potential security weaknesses, documenting findings and recommending remediation.

## Disclaimer
This is an educational portfolio project based on a sample endpoint security dataset. Findings represent the information available in the dataset and do not establish that any endpoint was compromised.