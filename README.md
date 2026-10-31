<p align="center">
  <img src="threat-monitor.svg" width="100%" alt="KF. / Cybersecurity — Security, with perspective. Kency Francois, Miami, FL. Purple-accented editorial header with a decorative security network." />
</p>

# Kency Francois

**Security Analyst | Miami, Florida**

**Security Operations · Threat Detection · Threat Intelligence**

FIU Information Systems graduate and CompTIA Security+ certified analyst with **one year of enterprise Information Security Analyst internship experience at Willkie Farr & Gallagher LLP**. My professional work spans security alert triage, SIEM/EDR and authentication investigations, and vulnerability reporting. Independent projects focus on AWS detection engineering and Microsoft Entra ID.

[Portfolio](https://kfran127.github.io/) · [LinkedIn](https://linkedin.com/in/kency-francois) · [Email](mailto:kencyfrancoiss@gmail.com)

## `01 / selected projects`

### Engineering detection. Investigating threats.

Selected work and upcoming projects spanning cloud detection engineering, AI-assisted security investigations, and enterprise threat hunting.

### Project 01 — AWS IAM Privilege Escalation Detection & Incident Response

**Cloud Detection Engineering · Status: Completed**

Engineered an AWS-native detection pipeline to identify selected high-risk IAM permission changes, generate structured security alerts, and support evidence-based investigation and manual containment.

**Implemented architecture:** AWS CloudTrail → CloudWatch Logs subscription filter → Python Lambda → Amazon SNS

**Validation:** Three detection rules implemented. Only the `AdministratorAccess` policy attachment rule was validated end-to-end in real AWS; the other two were tested with synthetic inputs. Containment was manual: the elevated permission was removed after reviewing CloudTrail evidence.

**Technologies:** AWS CloudTrail · Amazon CloudWatch Logs · AWS Lambda · Python · Amazon SNS · AWS IAM

[Explore Project on GitHub](https://github.com/kfran127/aws-iam-privilege-escalation-detection)

### Project 02 — SentinelAI: AI-Powered AWS Threat Investigation

**AI-Assisted Threat Investigation / Threat Intelligence · Status: Planned**

An upcoming AI-assisted AWS security investigation system designed to analyze suspicious API activity from unfamiliar source IP addresses, enrich relevant indicators with threat intelligence, and generate evidence-grounded investigation reports.

**Initial scope:** One simulated unfamiliar-source-IP investigation with source-attributed intelligence and evidence-linked reporting. An unfamiliar IP is not proof of compromise; remediation is outside version 1.

**Proposed technologies:** AWS CloudTrail · Python · Boto3 · OpenAI API · VirusTotal API · AbuseIPDB API · MITRE ATT&CK

*Planned Project*

### Project 03 — Enterprise SIEM Detection Engineering & Threat Hunting

**SIEM Detection Engineering / Threat Hunting · Status: Planned**

An upcoming AWS-hosted SIEM lab using a Windows Server EC2 instance for endpoint security telemetry and a separate Linux EC2 instance running Splunk Enterprise to develop SPL detections and investigate suspicious activity.

**Planned architecture:** Windows Server EC2 (Windows Event Logs + Sysmon) → Splunk Universal Forwarder → restricted private-VPC telemetry forwarding → Splunk Enterprise on a separate Linux EC2 instance. A MacBook will provide remote administration. CloudTrail → S3 → Splunk integration is a future expansion, outside the initial scope.

**Proposed technologies:** AWS EC2 · AWS VPC · AWS Security Groups · Windows Server · Windows Event Logs · Sysmon · Splunk Universal Forwarder · Linux · Splunk Enterprise · SPL · MITRE ATT&CK

*Planned Project*

### Project 04 — SecureBank IAM Lab

**Identity & Access Management · Status: Completed**

Designed and implemented a simulated banking identity environment in Microsoft Entra ID, incorporating Conditional Access, Privileged Identity Management, access reviews, and identity monitoring. Practiced identity lifecycle workflows and queried sign-in and audit logs through Azure Log Analytics.

**Technologies:** Microsoft Entra ID · Conditional Access · Privileged Identity Management · Access Reviews

[View Project on GitHub](https://github.com/kfran127/securebank-iam-lab)

## `02 / professional experience`

### Willkie Farr & Gallagher LLP

**Information Security Analyst Intern | June 2025 – June 2026**

- Monitored and triaged **100+ weekly security alerts** across QRadar, CrowdStrike, Varonis, Duo Security, and Cisco Intelligence, documenting investigation findings and resolutions.
- Investigated suspicious domains, IPs, endpoint activity, and Citrix authentication alerts using SIEM/EDR telemetry, threat intelligence, historical IP activity, and Duo MFA verification. Reviewed CrowdStrike alerts, retrieved suspicious files through a **separate sandbox platform**, and analyzed samples with VirusTotal.
- Prepared monthly Qualys vulnerability reports across departments, organizing findings in Excel and highlighting vulnerabilities requiring remediation for senior security review.

## `03 / technical skills`

**Professional experience:** Alert triage · SIEM/EDR investigations · Authentication review · IOC analysis · Threat intelligence research · Vulnerability reporting · Investigation documentation

**Professional tools:** IBM QRadar · CrowdStrike Falcon · Varonis · Duo Security · Qualys · IBM X-Force · AlienVault OTX · VirusTotal · AbuseIPDB · Cisco Intelligence · Cisco Prime · SolarWinds

**Personal labs:** AWS IAM · AWS CloudTrail · Amazon CloudWatch Logs · AWS Lambda · Amazon SNS · Microsoft Entra ID · Conditional Access · Privileged Identity Management · Access Reviews

**Developing skills:** Python (Learning) · Detection engineering · Threat hunting · Security automation · KQL / Azure Log Analytics (lab exposure)

## `04 / education & certifications`

**Florida International University** — BBA Information Systems · May 2026 · GPA: 3.70

**CompTIA Security+** — January 2025

**CompTIA CySA+** — In Progress

## `05 / connect`

[Portfolio](https://kfran127.github.io/) · [LinkedIn](https://linkedin.com/in/kency-francois) · [GitHub](https://github.com/kfran127) · [Email](mailto:kencyfrancoiss@gmail.com)
