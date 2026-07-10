# Domain 4: Security Operations

**Date:** Jul 9, 2026 | **Status:** Complete ✅

## Sections Completed
- 4.1: Security Techniques
- 4.2: Asset Management
- 4.3: Vulnerability Management
- 4.4: Security Monitoring
- 4.5: Enterprise Security
- 4.6: Identity & Access Management
- 4.7: Automation & Orchestration
- 4.8: Incident Response
- 4.9: Security Data Sources

## 4.1 Security Techniques
- Secure baselines and hardening for endpoints, servers, network devices, cloud, and mobile devices.
- Wireless security: WPA2/WPA3, site surveys, heat maps, and secure configuration.
- Application security: input validation, code signing, secure cookies, sandboxing, and monitoring.
- Goal: reduce attack surface and keep systems configured to a known secure state.

## 4.2 Asset Management
- Inventory hardware, software, and data assets.
- Track ownership, classification, location, and lifecycle status.
- Secure procurement, assignment, monitoring, disposal, and decommissioning.
- Goal: know what exists, who owns it, and how sensitive it is.

## 4.3 Vulnerability Management
- Identify vulnerabilities through scans, assessments, threat intel, and testing.
- Analyze and prioritize findings using risk, severity, and business impact.
- Remediate with patching, configuration changes, segmentation, or compensating controls.
- Validate fixes and report on results.

## 4.4 Security Monitoring
- Monitor logs, endpoints, servers, applications, and network traffic.
- Activities: log aggregation, alerting, scanning, reporting, and tuning detections.
- Tools: SIEM, antivirus, DLP, vulnerability scanners, SNMP, NetFlow.
- Goal: detect suspicious behavior early and respond faster.

## 4.5 Enterprise Security
- Strengthen security with firewalls, IDS/IPS, NAC, EDR/XDR, web filters, and secure protocols.
- Improve email protection with SPF, DKIM, and DMARC.
- Use OS and network security controls like Group Policy, ACLs, SELinux, and segmentation.
- Goal: improve enterprise defenses through layered controls.

## 4.6 Identity & Access Management
- Provisioning and deprovisioning user accounts.
- Enforce least privilege, role-based access, MFA, SSO, federation, and password policies.
- Protect privileged accounts with vaulting, just-in-time access, and strong auditing.
- Goal: ensure the right users have the right access at the right time.

## 4.7 Automation & Orchestration
- Automate repetitive security tasks like provisioning, alert handling, scanning, and reporting.
- Use orchestration to connect tools and improve workflow efficiency.
- Benefits: speed, consistency, reduced human error.
- Risks: complexity, bad logic at scale, and over-reliance on automation.

## 4.8 Incident Response
- Lifecycle: preparation, detection, analysis, containment, eradication, recovery, lessons learned.
- Practice with tabletop exercises, simulations, and playbooks.
- Includes root cause analysis, threat hunting, and evidence handling.
- Goal: respond quickly, contain damage, and improve future readiness.

## 4.9 Security Data Sources
- Use logs from firewalls, servers, endpoints, applications, and identity systems.
- Review packet captures, metadata, alerts, vulnerability scans, dashboards, and reports.
- Correlate multiple data sources to understand scope, timeline, and impact.
- Goal: support investigations with accurate evidence and context.

**THM Tie-in:** SOC Level 1, Cyber Defense, and logging/alert triage rooms match Domain 4 very well because they focus on monitoring, incident handling, and investigation workflow.

## Hands-On Linux Practice (Domain 4)
- Warmup: `mkdir domain4-lab && cd domain4-lab`
- Create sample log: `echo "Failed login from 192.168.1.50" > auth.log`
- Verify: `cat auth.log`, `grep "Failed" auth.log`, `ss -tuln`, `ps aux | head`
- Cleanup: `cd .. && rm -rf domain4-lab`
- Ties to 4.4 and 4.9: monitoring, log review, and investigation basics.
