# Domain 2: Threats, Vulnerabilities, & Mitigations (22%)

**Date:** Feb 25, 2026 | **Status:** Complete ✅

## Sections Completed
- 2.1: Threat Actors & Motivations
- 2.2: Threat Vectors & Attack Surfaces
- 2.3: Vulnerabilities
- 2.4: Malicious Activity
- 2.5: Mitigations

## 2.1 Threat Actors & Motivations
- Types: Nation-state, unskilled attackers, hacktivists, insiders, organized crime, shadow IT.
- Motivations: Money, espionage, ideology, revenge.

## 2.2 Threat Vectors & Attack Surfaces
- Message-based: phishing, spear phishing, vishing, smishing; social engineering and pretexting.
- File/image-based, drive-by downloads, and removable media (USB, rogue devices).
- Technical: software vulns, misconfigured services, unsecure Wi‑Fi, open ports, default credentials, exposed APIs, supply chain compromise.
- Attack surface: all ways an attacker can interact with a system; reduced through hardening, segmentation, and minimizing exposed services.

## 2.3 Vulnerabilities
- Application/OS: injection (SQL, command), buffer overflow, race conditions, insecure deserialization, EOL or unpatched systems, misconfigured cloud services.
- Crypto: weak algorithms, key reuse, poor key storage, downgrade attacks, collisions.
- Third-party: libraries, dependencies, SaaS, vendor/supply chain risks.

## 2.4 Malicious Activity
- Network: DDoS, DNS attacks (domain hijacking, URL redirection), on‑path (MITM), anomalous traffic or impossible travel.
- Application: XSS, injection, privilege escalation, strange log entries or file changes.
- Crypto/password: downgrade attempts, collisions, password spraying, brute force, account lockouts.
- Malware: ransomware, Trojans, worms, viruses; unexpected resource usage or blocked/redirected content.

## 2.5 Mitigations
- Architecture: segmentation (VLANs, security zones), isolation, DMZs; minimize attack surface.
- Controls: access controls, ACLs, app allowlisting/denylisting, strong authentication, least privilege.
- Maintenance: patching, configuration management, decommissioning old systems, endpoint protection and host firewalls.
- Visibility: encryption for data in transit/at rest, monitoring via SIEM and logs, hardening baselines, continuous risk assessments.

**THM Tie-in:** Pre-Security rooms (phishing, threats)

## Hands-On Linux Practice (Feb 26)
- Warmup: `touch cyber-feb26.txt; echo "Domain 2 practice" > cyber-feb26.txt`
- Verified: `cat` (content), `grep "Domain"` (filter), `rm` (cleanup) in `/tmp`
- Ties to 2.3: Vuln scanning/logs (basic file changes and text filtering).
