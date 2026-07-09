# Domain 3: Security Architecture (18%)

**Date:** Jul 9, 2026 | **Status:** Complete ✅

## Sections Completed
- 3.1: Architecture Models
- 3.2: Enterprise Infrastructure
- 3.3: Data Protection
- 3.4: Resilience & Recovery

## 3.1 Architecture Models
- Models: on-prem, cloud, hybrid, multi-cloud, centralized, decentralized.
- Technologies: virtualization, containers, serverless, microservices, Infrastructure as Code (IaC).
- Specialized environments: IoT, OT, ICS/SCADA, RTOS, embedded systems.
- Key idea: architecture choices affect security, availability, scalability, and patching.

## 3.2 Enterprise Infrastructure
- Devices: firewalls, IDS/IPS, proxies, load balancers, VPN concentrators, sensors, WAF, NGFW.
- Design concepts: segmentation, security zones, DMZ, attack surface reduction, port security.
- Placement matters: where controls sit in the network affects visibility and protection.
- Goal: apply security principles to infrastructure, not just add tools after the fact.

## 3.3 Data Protection
- Data states: at rest, in transit, in use.
- Methods: encryption, hashing, masking, tokenization, obfuscation, segmentation.
- Data concerns: sovereignty, geolocation, retention, classification, regulated and sensitive data.
- Goal: match protection method to the data type and business need.

## 3.4 Resilience & Recovery
- Availability concepts: redundancy, clustering, load balancing, fault tolerance, replication.
- Recovery options: backups, snapshots, hot/warm/cold sites, geographic dispersion, disaster recovery.
- Testing: tabletop exercises, failover drills, simulations, continuity checks.
- Supporting systems: UPS, generators, capacity planning, multi-site resilience.

**THM Tie-in:** Networking, defensive security, and SOC-style labs that reinforce segmentation, logging, architecture choices, and layered defense.

## Hands-On Linux Practice (Domain 3)
- Warmup: `mkdir domain3-lab && cd domain3-lab`
- Create notes: `echo "Security Architecture practice" > domain3.txt`
- Verify: `cat domain3.txt`, `ip a`, `ss -tuln`, `ls -la`
- Cleanup: `cd .. && rm -rf domain3-lab`
- Ties to 3.2: network visibility, open ports, and infrastructure awareness.
