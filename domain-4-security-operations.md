# Domain 4: Security Operations

**Date:** Jul 9, 2026 | **Status:** In Progress ⏳

## 4.1 Security Techniques
- Secure endpoints, servers, mobile devices, and network appliances with hardening and baselines.
- Apply secure configs to cloud, wireless, IoT, OT/ICS, and specialized systems.

## 4.2 Asset Management
- Track hardware, software, and data assets through inventory, ownership, classification, and monitoring.
- Secure procurement, maintenance, reuse, decommissioning, and disposal processes.

## 4.3 Vulnerability Management
- Identify, analyze, prioritize, remediate, and validate vulnerabilities.
- Use scans, patching, risk ratings, and reporting to reduce exposure.

## 4.4 Alerting & Monitoring
- Monitor logs, events, flows, and endpoint activity with SIEM, scanners, AV, DLP, SNMP, and NetFlow.
- Correlate alerts and tune monitoring to reduce false positives and improve visibility.

## 4.5 Enterprise Security Enhancement
- Strengthen security with firewalls, IDS/IPS, DNS filtering, email protections, NAC, FIM, EDR/XDR, and DLP.
- Improve OS security, secure protocols, segmentation, and behavior analytics.

## 4.6 Identity & Access Management
- Manage provisioning, deprovisioning, permissions, access reviews, and account policies.
- Enforce least privilege, MFA, role-based access, and lifecycle management.

## 4.7 Automation & Orchestration
- Use scripts, workflows, and orchestration tools to speed response and reduce manual errors.
- Automate repetitive security tasks like alert handling, ticketing, and remediation steps.

## 4.8 Incident Response
- Follow the lifecycle: preparation, detection, analysis, containment, eradication, recovery, lessons learned.
- Use playbooks, tabletop exercises, root cause analysis, and forensics procedures.

## 4.9 Investigation Data Sources
- Use logs from endpoints, servers, apps, firewalls, IDS/IPS, proxies, and cloud platforms.
- Correlate packet captures, network flows, metadata, and audit logs to support investigations.

**THM Tie-in:** SOC Level 1, Cyber Defense, and logging/alert triage rooms match Domain 4 very well because they focus on monitoring, incident handling, and investigation workflow.

## Hands-On Linux Practice (Domain 4)
- Warmup: `mkdir domain4-lab && cd domain4-lab`
- Create a log file: `echo "failed login from 10.0.0.5" > security.log`
- Review data: `cat security.log`, `grep "failed" security.log`, `ss -tuln`, `ps aux`
- Cleanup: `cd .. && rm -rf domain4-lab`
