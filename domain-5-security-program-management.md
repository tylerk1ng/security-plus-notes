# Domain 5: Security Program Management

**Date:** Jul 9, 2026 | **Status:** In Progress ⏳

## 5.1 Security Governance
- Governance includes policies, standards, procedures, and guidelines that shape security decisions.
- Key areas include acceptable use, access control, password policy, physical security, encryption, and change management.

## 5.2 Risk Management
- Identify, assess, and prioritize risks using qualitative and quantitative methods.
- Risk responses include accepting, avoiding, transferring, mitigating, and documenting risk in a register.

## 5.3 Third-Party Risk
- Vendors and partners create supply chain risk that must be reviewed and monitored.
- Use due diligence, contracts, SLAs, NDAs, right-to-audit clauses, and assessments.

## 5.4 Audits & Assessments
- Internal, external, attestation, and compliance audits help validate security posture.
- Common assessments include penetration tests, vulnerability scans, control reviews, and gap analysis.

## 5.5 Security Awareness
- Train users on phishing, social engineering, password hygiene, acceptable use, and incident reporting.
- Awareness programs should be continuous, measurable, and updated for current threats.

## 5.6 Business Impact & Resilience
- Business impact analysis helps identify critical systems and recovery priorities.
- Know RTO, RPO, MTTR, and MTBF for continuity and recovery planning.

## 5.7 Compliance & Oversight
- Security programs must align with legal, regulatory, and organizational requirements.
- Oversight includes documentation, reviews, accountability, and continuous improvement.

**THM Tie-in:** SOC and blue-team labs support awareness of policy, reporting, risk, and documentation, even though this domain is more governance-focused than hands-on.

## Hands-On Linux Practice (Domain 5)
- Warmup: `mkdir domain5-lab && cd domain5-lab`
- Create a policy note: `echo "Security governance and risk review" > governance.txt`
- Review content: `cat governance.txt`, `ls -la`, `chmod 600 governance.txt`
- Cleanup: `cd .. && rm -rf domain5-lab`
