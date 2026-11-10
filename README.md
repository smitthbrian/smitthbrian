<h1 align="center">Brian Smith</h1>
<p align="center">
  <b>GRC Engineer @ Ally Financial</b><br>
  Network Infrastructure · Governance, Risk & Compliance · Cybersecurity<br>
  📍 Charlotte, NC
</p>

---

## About

I'm a GRC Engineer at Ally Financial, working where network infrastructure, compliance, and cybersecurity meet. I design and maintain automated pipelines that replace manual, error-prone audit processes with defensible, repeatable evidence collection at scale.

The technical side of that spans Python, network-data ETL, vulnerability management, Splunk instrumentation, GitLab CI/CD, and AI-assisted tooling through MCP integrations and agentic coding sessions. The other side is translation: turning regulatory and audit requirements into architectural decisions, scoping findings to their root causes, leading remediation across teams, and serving as a primary point of contact for internal and regulatory audit engagements.

A core part of the job is acting as the first line of defense on our own architecture, identifying control gaps and design risks before they surface as formal findings. Knowing what an auditor will look for shapes both how I build and what I go looking for.

Many GRC programs still treat compliance as a scramble before the audit. Continuous, automated evidence of compliance is the better model, and it's what I'm building toward.

---

## What I Work On

**Privileged Activity Monitoring (PAM)**
- Administer and develop the privileged activity monitoring environment for an enterprise network engineering organization, a role I've held for over a year
- Own AAA and syslog configuration standards across a multi-vendor fleet: switches, routers, out-of-band console infrastructure, network packet brokers, and centralized management platforms (Fortinet, Arista, Cisco, OpenGear, Gigamon)

**Detection & evidence automation**
- Building a pipeline that consolidates AAA accounting logs, raw syslog, and management-platform audit logs into a single normalized source
- Activity is automatically evaluated against roughly a dozen detection checks, including:
  - Unauthorized or out-of-policy commands
  - Brute-force indicators and excessive failed logins
  - Network changes with no associated change record, incident, or vendor support case
  - Changes made outside approved change windows
- Integrates with ServiceNow, Splunk, FortiManager, and Arista CloudVision APIs to correlate activity against change records and device state
- Developed with Claude Code and MCP integrations, with the goal of producing continuous, audit-ready evidence instead of point-in-time samples

**Findings management & remediation**
- Manage GRC findings for the network space end to end: scoping, root cause, stakeholder coordination, remediation tracking, and closure evidence
- Drive the technical solutions behind remediation, not just the paperwork
- Example: helped develop and track a fleet-wide local credential rotation process that covers hundreds of network devices in a single maintenance window, satisfying both scheduled and offboarding-triggered rotation requirements

**Audit engagement**
- Primary point of contact for internal and regulatory audit requests in my area
- Translate control language into what the infrastructure actually does, and into what evidence proves it

> Details of this work are proprietary, so it's described here in general terms and the code lives in private repositories.

---

## Experience

**GRC Engineer · Ally Financial** · Charlotte, NC · 2025 – Present  
Connectivity Services. Privileged activity monitoring, compliance automation, findings remediation, and audit support across enterprise network infrastructure.

**Cybersecurity Intern · InfusionPoints, LLC**  
- Rotated across Cloud Operations, Advisory, Engineering, and SOC teams supporting federal and enterprise security work
- Built **SOWForge**, a VBA automation that standardized Statement of Work generation and cut turnaround from hours to minutes
- Developed **BioBot**, a multi-cloud (AWS/GCP) workflow to collect, approve, and publish employee bios
- Supported a FedRAMP High SSP uplift by mapping access control requirements from NIST 800-53 Rev. 4 to Rev. 5

---

## Skills & Tools

| Area | Tools |
|---|---|
| **Languages & query** | Python, Splunk SPL, SQL, PowerShell, VBA |
| **Automation & integration** | REST APIs (ServiceNow, Splunk, FortiManager, Arista CloudVision), GitLab CI/CD, ETL pipelines, Claude Code, MCP |
| **Network & security infrastructure** | Fortinet (FortiGate, FortiManager, FortiAnalyzer), Arista, Cisco, F5 BIG-IP, OpenGear, Gigamon; TACACS+/AAA, syslog |
| **Monitoring & SIEM** | Splunk, SolarWinds, Wireshark |
| **GRC & systems of record** | ServiceNow, Archer, Jira, Confluence, SharePoint; NIST 800-53, FFIEC, FedRAMP |
| **Cloud** | AWS (EC2, S3, API Gateway, DynamoDB) |
| **Security tooling** | Nessus, Amazon Inspector, Burp Suite, Nmap, Hashcat, Snort, Metasploit |

**Certifications**
- AWS Certified Solutions Architect – Associate
- AWS Certified Cloud Practitioner
- Microsoft Excel (Office 365)
- *In progress:* CompTIA Security+

**Education**  
BSBA, Computer Information Systems (Cybersecurity concentration), Walker College of Business, Appalachian State University, 2025

---

## Projects

My current work is private. The public repositories below are from my internship and coursework.

**Automation**
- [**BioBot**](https://github.com/smitthbrian/BioBot): AWS/GCP form submission and approval workflow for collecting and publishing employee bios
- **SOWForge** *(private)*: VBA-powered Word automation with Excel content mapping for generating Statements of Work
- [**Salesforce–QuickBooks ETL Integration**](https://github.com/smitthbrian/ETL-Project): ETL pipelines syncing invoicing and payments to eliminate manual data entry

**Security operations & network defense**
- [**Wireshark Incident Report**](https://github.com/smitthbrian/Wireshark-Incident-Report-): network forensics and anomaly detection from packet captures in a simulated incident
- [**Web Access Log Audit**](https://github.com/smitthbrian/Password-Audit-Simulation): log analysis identifying reconnaissance activity and malware indicators
- [**Remote Access VPN & Network Defense**](https://github.com/smitthbrian/VPN): pfSense and OpenVPN with access controls, firewall rules, and certificate-based authentication
- [**Zero Trust Architecture Implementation**](https://github.com/smitthbrian/Zero-Trust-Architecture-Implementation)

**Risk & compliance**
- [**Incident Disclosure Report**](https://github.com/smitthbrian/Incident-Disclosure-Mock-Report): legal analysis and executive report for a simulated breach under SOX, GLBA, and GDPR
- [**Ransomware and Least Privilege**](https://github.com/smitthbrian/Ransomware-and-Least-Privilege-Project): how least-privilege enforcement reduces ransomware risk

**Offensive security labs**
- [**Password Cracking: Windows & Kali**](https://github.com/smitthbrian/Password-Cracking): NTLM hash extraction, Wireshark, and Hashcat on VMs
- [**Liber8tion Password Cracking Simulation**](https://github.com/smitthbrian/Network-Traffic-Analysis): password dump analysis with rockyou and Hashcat
- [**SQL Injection Vulnerabilities**](https://github.com/smitthbrian/SQL-Injection-Vulnerabilities): injection techniques and secure-coding defenses with ASPX and MariaDB
- [**Web Application Vulnerabilities**](https://github.com/smitthbrian/Web-Application-Vulnerabilities-Simulation): XSS, CSRF, session hijacking, and file upload abuse, with mitigations

**Data**
- [**Database Management (MySQL)**](https://github.com/smitthbrian/Database-Management---Cumulative-MySQL-Code): schema design, normalization, and queries for a mock business

---

## Beyond Work

- **Ranger & Kitchen Manager, Philmont Scout Ranch**: led backcountry backpacking crews and trained staff in safety and leadership
- **Eagle Scout**: organized volunteers to restore 30+ bikes and rehabilitate local trails used by children's programs

---

## Contact

- [LinkedIn](https://www.linkedin.com/in/briansmith2025/)
- Email: smitthbrian2@gmail.com
