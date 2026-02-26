# Domain 2: Threats, Vulnerabilities, & Mitigations

**Date:** Feb 25, 2026 | **Status:** In Progress ✅

## 2.1 Threat Actors & Motivations
- Types: Nation-state, hacktivists, insiders, cybercriminals.
- Motivations: Money vs. mission; skill levels from script kiddies to APTs.

## 2.2 Threat Vectors & Surfaces
- Message-based (phishing, vishing), file/image-based, removable media.
- Software vulns, unsecure networks, open ports, default creds, supply chain.

## 2.3 Vulnerabilities
- App/OS: Injection, buffer overflow, EOL systems, cloud misconfigs.
- Crypto flaws, improper configs, third-party risks.

## 2.4 Malicious Indicators
- Network: DDoS, on-path; app: XSS, escalation; crypto: downgrades.
- Ransomware, anomalies like password spraying.

## 2.5 Mitigations
- Segmentation (VLANs), access controls, app allowlisting, patching.
- Encryption, monitoring (SIEM), least privilege, hardening.

**THM Tie-in:** Pre-Security rooms (phishing, threats).

## Hands-On Linux Practice (Feb 26)
- Warmup: `touch cyber-feb26.txt; echo "Domain 2 practice" > cyber-feb26.txt`
- Verified: `cat` (content), `grep "Domain"` (filter), `rm` (cleanup) in /tmp
- Ties to 2.3: Vuln scanning/logs.
