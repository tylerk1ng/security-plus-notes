# Domain 1: General Security Concepts (12%)

**Date:** Feb 25, 2026 | **Status:** Complete ✅


## Sections Completed
- 1.1: Security Controls (technical, managerial, operational, physical)
- 1.2: Fundamental Concepts (CIA Triad, AAA, Zero Trust, non-repudiation)
- 1.3: Change Management (business processes, technical change control, rollback)
- 1.4: Cryptographic Solutions (PKI, encryption, obfuscation, hashing, blockchain)

## Security Controls (1.1)
- **By implementation**: technical, managerial, operational, physical.  
- **By function**: preventive, deterrent, detective, corrective, compensating, directive.

## Fundamental Concepts (1.2)
- **CIA Triad**
  - Confidentiality: encryption, access controls, permissions.
  - Integrity: hashing, checksums, digital signatures.
  - Availability: redundancy, backups, fault tolerance.
- **AAA**
  - Authentication: passwords, biometrics, MFA.
  - Authorization: RBAC, least privilege, assigned permissions.
  - Accounting: logging, monitoring, audit trails.
- **Zero Trust**
  - Never trust by default; verify explicitly.
  - Use least privilege, adaptive identity, and policy-based access.
- **Non-repudiation**
  - Proves a user or sender cannot deny an action.
  - Commonly supported by hashing and digital signatures.
- **Gap analysis**
  - Compares current security posture to the desired state.
  - Helps identify missing controls or weak areas.
- **Physical security**
  - Locks, badges, cameras, guards, and facility controls.

## Change Management (1.3)
- Formal process: request, review, approval, scheduling, implementation, documentation.
- Reduces risk of outages and security gaps by ensuring changes are tested, communicated, and rolled back safely when needed.
- Includes identifying stakeholders, assessing risk, sandbox testing, and having a clear backout/rollback plan.

## Cryptographic Solutions (1.4)
- **Encryption**: symmetric/asymmetric, TLS, disk/file encryption; protects confidentiality.
- **Hashing & integrity**: hashes, salting, HMAC, digital signatures; protects integrity and non‑repudiation.
- **PKI & key management**: certificates, CAs, key exchange, revocation.
- **Other**: obfuscation, secure enclaves/TPM/HSM, blockchain concepts where relevant. 

## Key Takeaways
- 1.2 is the foundation: CIA, AAA, Zero Trust, non-repudiation, gap analysis, and physical security all connect to everyday security decisions.
- Change management protects security by making system changes controlled and reversible.
- Cryptographic solutions must match the goal: confidentiality, integrity, authentication, or non-repudiation.
