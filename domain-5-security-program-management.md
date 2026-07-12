# Domain 5: Security Program Management & Oversight (20%)

**Date:** Jul 9, 2026 | **Status:** Complete ✅


## Sections Completed
- 5.1: Security Governance
- 5.2: Risk Management
- 5.3: Third-Party Risk
- 5.4: Security Compliance
- 5.5: Audits & Assessments
- 5.6: Security Awareness

## 5.1 Security Governance
- Governance sets the rules, structure, and direction for an organization’s security program.
- Includes policies, standards, procedures, and guidelines.
- Common examples: acceptable use policy, password policy, access control policy, change management, onboarding, and offboarding.
- Defines roles and responsibilities such as data owner, data custodian, and users.

## 5.2 Risk Management
- Identify, assess, analyze, and track risks to the organization.
- Use qualitative and quantitative methods to measure likelihood and impact.
- Key terms: risk appetite, risk tolerance, risk register, exposure factor, and business impact analysis.
- Risk responses: mitigate, accept, transfer, avoid, exemption, and exception.
- Recovery metrics: RPO, RTO, MTTR, and MTBF.

## 5.3 Third-Party Risk
- Evaluate vendors, service providers, and partners before and during business relationships.
- Review supply chain risk, due diligence, monitoring, and vendor performance.
- Common agreements: SLA, MOU, NDA, BPA, MSA, and statements of work.
- May include right-to-audit clauses, questionnaires, penetration testing, and rules of engagement.

## 5.4 Security Compliance
- Understand and align with laws, regulations, standards, and frameworks.
- Common examples: GDPR, HIPAA, PCI-DSS, ISO 27001, NIST, and CIS benchmarks.
- Map internal policies and controls to compliance requirements and document evidence.
- Work with legal, audit, and business teams to manage findings, remediation, and reporting.
- Goal: ensure the organization can demonstrate it meets required obligations.

## 5.5 Audits & Assessments
- Audits confirm whether controls and processes are working as expected.
- Types: internal, external, attestation, compliance, and regulatory audits.
- Assessments may include gap analysis, self-assessments, and control reviews.
- Goal: verify compliance, identify weaknesses, and improve the security program.

## 5.6 Security Awareness
- Train users to recognize phishing, social engineering, suspicious behavior, and policy violations.
- Teach secure handling of passwords, removable media, sensitive data, and reporting procedures.
- Awareness should include onboarding, recurring training, role-based training, and incident reporting.
- Goal: reduce human error and build a stronger security culture.

**THM Tie-in:** Governance, phishing awareness, SOC processes, and labs that reinforce reporting, procedures, and security culture.

## Hands-On Linux Practice (Domain 5)
- Warmup: `mkdir domain5-lab && cd domain5-lab`
- Create policy note: `echo "Least privilege and acceptable use" > policy.txt`
- Verify: `cat policy.txt`, `chmod 600 policy.txt`, `ls -l`, `grep "least" policy.txt`
- Cleanup: `cd .. && rm -rf domain5-lab`
- Ties to 5.1, 5.4, and 5.6: governance, permissions, policy awareness, and evidence of control.
