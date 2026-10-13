<p align="center">
  <img src="threat-monitor.svg" width="100%" alt="Dark global cyber threat monitoring illustration with cyan network paths. Decorative artwork, not live telemetry." />
</p>

# Kency Francois

**Security Analyst · Miami, FL**<br>
Security operations · Threat intelligence · Cloud detection & identity security

[Portfolio](https://kfran127.github.io) · [LinkedIn](https://linkedin.com/in/kency-francois) · [GitHub](https://github.com/kfran127)

**CompTIA Security+ — Certified** · **CompTIA CySA+ — In Progress**

---

## `01 / analyst profile`

I'm a Florida International University Information Systems graduate with **one year of Information Security Analyst internship experience at Willkie Farr & Gallagher LLP**. My work focused on enterprise security alert triage, SIEM/EDR investigations, threat intelligence, and vulnerability management.

Outside of professional experience, I build documented security labs in AWS and Microsoft Entra ID to strengthen my understanding of detection engineering, identity security, and incident response. I'm continuing to develop my Python and cloud security skills.

### Willkie Farr & Gallagher LLP

**Information Security Analyst Intern · June 2025 – June 2026**

- **Security operations:** Monitored and triaged 100+ weekly alerts across enterprise security tools, documenting investigations and resolutions.
- **Investigations & threat intelligence:** Reviewed suspicious domains, IPs, executable downloads, endpoint activity, and authentication alerts using SIEM/EDR telemetry and supporting analysis tools.
- **Vulnerability management:** Reviewed Qualys scan reports, tracked remediation progress, and contributed to internal procedure documentation.

## `02 / technical skills`

**Professional experience — security operations**<br>
Alert triage · SIEM/EDR investigations · IOC analysis · Threat intelligence · Vulnerability management · Investigation documentation<br>
Tools: IBM QRadar · CrowdStrike Falcon · Varonis · Qualys · Duo Security · Cisco Intelligence · VirusTotal · Cisco Prime · SolarWinds

**Personal labs — cloud security & identity**<br>
AWS IAM · AWS CloudTrail · Amazon CloudWatch Logs · AWS Lambda · Amazon SNS · Microsoft Entra ID · Conditional Access · Privileged Identity Management · Access reviews

**Developing skills**<br>
Python (learning) · AWS detection automation · KQL / Azure Log Analytics (lab exposure)

## `03 / completed projects`

### [AWS IAM Privilege Escalation Detection & Incident Response](https://github.com/kfran127/aws-iam-privilege-escalation-detection)

**Status: Completed · Authorized AWS security lab**

Built an AWS-native pipeline to detect selected high-risk IAM permission changes and deliver structured email alerts.

- Connected **CloudTrail → CloudWatch Logs subscription filter → Python Lambda → Amazon SNS**.
- Implemented three narrowly scoped detection rules for privileged policy attachment, administrative group membership changes, and IAM policy version modifications.
- **Validated one rule end-to-end in AWS:** attached `AdministratorAccess` to a controlled test user and received a real **CRITICAL** SNS email alert.
- Investigated the CloudTrail event, manually removed the elevated permission, and documented the response.
- Tested the remaining two rules using synthetic events; they have **not** been validated end-to-end in AWS.

`AWS IAM` `CloudTrail` `CloudWatch Logs` `Lambda` `Python` `SNS`

[Explore the architecture, detection rules, tests, and incident report →](https://github.com/kfran127/aws-iam-privilege-escalation-detection)

### [SecureBank IAM Lab](https://github.com/kfran127/securebank-iam-lab)

**Status: Completed · Personal lab / simulated banking environment**

Built a Microsoft Entra ID lab focused on identity lifecycle management, least privilege, and access governance.

- Practiced Joiner/Mover/Leaver workflows and group-based access assignments.
- Configured Conditional Access policies, including phishing-resistant MFA requirements for administrators.
- Configured recurring access reviews and explored privileged access governance.

`Microsoft Entra ID` `Conditional Access` `PIM` `Access Reviews`

[Explore the identity security lab →](https://github.com/kfran127/securebank-iam-lab)

## `04 / project roadmap`

The following work is in development or planned. Descriptions are goals, **not completed results**.

### AWS Password Spraying Detection Lab

**Status: In Development**

Design a detection for repeated failed AWS console sign-ins affecting multiple IAM users from a common source IP. Investigate available CloudTrail telemetry and test correlation logic with clearly labeled synthetic events.

**Proposed stack:** AWS CloudTrail · CloudWatch Logs · Lambda · Python · SNS

### AI-Powered SOC Investigation Assistant

**Status: Planned**

Prototype a Python-based assistant that turns sample security alerts into structured investigation summaries, preserves links to supporting evidence, and keeps decisions with a human analyst.

**Proposed focus:** Alert triage · Evidence preparation · LLM-assisted summaries · Analyst review · Evaluation

---

**Connect:** [Portfolio](https://kfran127.github.io) · [LinkedIn](https://linkedin.com/in/kency-francois) · [GitHub](https://github.com/kfran127)
