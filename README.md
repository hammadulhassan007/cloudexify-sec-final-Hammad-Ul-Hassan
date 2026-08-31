# CloudExify Cybersecurity Internship — Final Submission

**Lead Security Auditor:** Hammad Ul Hassan  
**Internship ID:** CX-INT-2026-CYB-0044  
**Submission Date:** August 31, 2026  


---

## Executive Overview

This repository contains the official deliverables for the **CloudExify Cybersecurity Summer Internship 2026**, with primary focus on **Project 4: Vulnerability Assessment & Remediation** alongside consolidated reports from previous assessment modules.

---

## Repository Structure

```text
cloudexify-sec-final-hammad/
│
├── README.md
├── vulnerability_assessment_report.pdf    # Primary: Project 4 Capstone Report
├── web_app_pentest_report.pdf             # Project 3: Web Application Pentest Report
├── penetration_test_report.pdf            # Project 2: Network & Auth Pentest Report
│
└── project_screenshots/                        #project 4 screenshots



```

Project 4: Vulnerability Assessment & Remediation (Primary Capstone)
Target System: Local Containerized Web Infrastructure (127.0.0.1:8080)
Tooling: Tenable Nessus Essentials v10.12.4, Docker Engine, Ubuntu Linux  
Duration: Single-Day Assessment (August 31, 2026) 
Key Findings:Audited 62 total findings across web, host, and transport layers. 
Identified and validated unauthenticated web.config File Information Disclosure (Plugin #121479, CVSS v3 Base Score: 5.3).  
Formulated remediation controls (Apache access restrictions for sensitive files and header disclosure suppression). 
Primary Deliverable: vulnerability_assessment_report.pdf


Consolidated Previous Projects SummaryProject 2: Network & Auth Penetration Testing (penetration_test_report.pdf)Evaluated custom authentication mechanisms (secure_auth.py), verified rate-limiting/account lockout controls against automated brute-force attacks, analyzed salted Bcrypt hashing, and performed network packet inspection via Wireshark and Nmap. 
Project 3: Web Application Penetration Testing (web_app_pentest_report.pdf)Assessed Damn Vulnerable Web Application (DVWA v1.10) using Burp Suite Community Edition, validating vulnerabilities across OWASP Top 10 categories including SQL Injection, Reflected XSS, CSRF, and Unrestricted File Upload.  
