# Domain 3: Security Architecture (18%)

**Date:** Jul 9, 2026 | **Status:** Complete ✅


## 3.1 Architecture Models
- Concepts: Enterprise, zero trust, defense in depth, secure by design.
- Framework thinking: segment systems, verify explicitly, assume breach.

## 3.2 Infrastructure Considerations
- Devices: firewalls, routers, switches, IDS/IPS, proxies, load balancers.
- Use cases: on-prem, cloud, hybrid, virtualization, IoT, OT/ICS.

## 3.3 Data Protection
- States of data: at rest, in transit, in use.
- Controls: encryption, hashing, tokenization, masking, DLP, key management.

## 3.4 Resilience & Recovery
- High availability: redundancy, failover, clustering, load balancing.
- Recovery concepts: backups, replication, snapshots, hot/warm/cold sites.

## 3.5 Cloud & Virtualization
- Service models: IaaS, PaaS, SaaS.
- Deployment models: public, private, hybrid, community; shared responsibility matters.

## 3.6 Secure Application Architecture
- Basics: SDLC, threat modeling, API security, input validation, least privilege.
- Environment separation: dev, test, staging, production.

## 3.7 Physical & Wireless Architecture
- Physical security: badge access, cameras, locks, mantraps, sensors.
- Wireless: WPA2/WPA3, segmentation, guest networks, rogue AP detection.

**THM Tie-in:** Pre-Security / Intro Networking / SOC Level 1 rooms tied to segmentation, architecture, logging, and layered defense.

## Hands-On Linux Practice (Domain 3)
- Warmup: `mkdir domain3-lab && cd domain3-lab`
- Create notes: `echo "Security Architecture practice" > domain3.txt`
- Verify: `cat domain3.txt`, `ls -la`, `ip a`, `ss -tuln`
- Cleanup: `cd .. && rm -rf domain3-lab`
