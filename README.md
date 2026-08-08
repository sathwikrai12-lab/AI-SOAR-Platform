# AI-Powered Security Orchestration, Automation and Response (SOAR) Platform

**Problem Statement Number:** PSAIAC_173
**Category:** Software (Cyber Security)
**SDG Mapping:** SDG 16 – Peace, Justice and Strong Institutions

## Problem Description
Security Orchestration, Automation, and Response (SOAR) — SOC analysts spend hours on repetitive alert triage. Industry needs a SOAR platform that automates enrichment, containment, and response playbooks for common security incidents.

## Objective
To develop an AI-powered Security Orchestration, Automation and Response (SOAR) platform that collects security alerts from multiple sources, uses AI to classify and prioritize incidents, enriches them with threat intelligence, and automates containment and response playbooks — reducing manual SOC alert-triage workload and response time.

## Proposed Technology Stack
- **Backend:** Python (FastAPI / Flask)
- **AI/ML:** Scikit-learn (Random Forest, XGBoost, Isolation Forest)
- **Security Tools:** Wazuh, Sysmon, Suricata/Zeek, MITRE ATT&CK mapping
- **Threat Intelligence:** VirusTotal API, AbuseIPDB API
- **Database:** PostgreSQL / SQLite
- **Frontend:** React / HTML-CSS-JavaScript
- **Deployment:** Docker

## AI Component
Machine learning-based alert severity classification (Random Forest / XGBoost) to automatically prioritize incidents.

## Team
| Roll Number | Name |
|---|---|
| 20231CCS0148 |Sathwik Rai B S  |
|  |  |
|  |  |
|  |  |

## Project Guide
[Your supervisor's name]

## Repository Structure
```
AI-SOAR-Platform/
├── backend/
├── frontend/
├── ai-model/
├── threat-intelligence/
├── response-engine/
├── database/
├── documentation/
├── dataset/
├── README.md
└── requirements.txt
```
