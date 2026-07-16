# Jonathan Rodriguez

### Cybersecurity Analyst — SOC · Threat Detection · Incident Response · Applied Security Research

[![Email](https://img.shields.io/badge/Email-Jonth.career%40pm.me-8A2BE2?style=flat-square&logo=protonmail&logoColor=white)](mailto:Jonth.career@pm.me)
[![GitHub](https://img.shields.io/badge/GitHub-TheChosenOne--start-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/TheChosenOne-start)
[![Location](https://img.shields.io/badge/Based%20in-Orlando%2C%20FL-informational?style=flat-square)](#)

Cybersecurity analyst with 14+ months of SOC experience in threat detection, incident
response, and building EDR-style detection labs. A network infrastructure background
gives me full-stack visibility — from the physical/network layer up through endpoint
telemetry — when hunting threats.

---

## Technical Skills

**Languages** — Python · TypeScript · Solidity · C++

**Detection & Response** — Sysmon · LimaCharlie EDR · Elastic Stack · Google SecOps ·
IOC Detection · Log Analysis · Threat Modeling · Incident Response

**Automation & Scripting** — PowerShell · Bash · n8n · WSL

**Network Security** — VLAN Segmentation · Firewall Configuration · Protocol Analysis ·
Network Monitoring

**Platforms & Tools** — Docker · Git · Linux (Kali) · PostgreSQL · Redis · Foundry (Anvil)

**Security Frameworks** — MITRE ATT&CK · NIST CSF · Defense-in-Depth · Zero Trust

---

## Featured Projects

| Project | What it is | Stack |
|---|---|---|
| **[Cross-Dex-Hunter-defence](https://github.com/TheChosenOne-start/Cross-Dex-Hunter-defence)** | Smart-contract security research toolkit for BNB Chain: read-only token/pool vetting, fork-simulated pre-deployment validation, and bug-bounty triage. Started as a cross-DEX arbitrage system; rigorous testing produced a documented **negative result** (systematic on-chain arb isn't profitable against co-located MEV searchers), and the safety infrastructure built to reach that conclusion — fork simulation, risk circuit breakers, whitelist-only execution core with no arbitrary-calldata path — was repurposed into a defensive toolkit. Explicit scope/authorization boundaries document what the code is built to do and, deliberately, what it refuses to do. 8/8 contract tests · 48/48 unit tests · 4/4 fork-integration tests. | TypeScript, Solidity, Foundry, Anvil, Vitest |
| **[Tor-Notion-Browser](https://github.com/TheChosenOne-start/Tor-Notion-Browser)** | Fully isolated, privacy-focused containerized workspace: a Chromium GUI routed through Tor + Privoxy so all outbound traffic stays anonymous, with a multi-container Docker Compose architecture and HTTPS-secured noVNC access via a Caddy reverse proxy. Optional gocryptfs (FUSE) encryption protects data at rest. | Docker, Tor, Caddy, gocryptfs, WSL |
| **IOC Detection & Response Lab** *(self-directed, write-up)* | Built a virtual SOC (2 Windows VMs + Linux server) simulating EDR workflows equivalent to Trellix HX. Deployed Sysmon + Elastic Stack + LimaCharlie for endpoint detection and log correlation; created custom IOCs (file hashes, registry paths, process names) and ran simulated attacks including PowerShell exploitation and lateral movement. | Sysmon, Elastic Stack, LimaCharlie |
| **AI System Security Research** *(vulnerability assessment, write-up)* | Conducted security research on a production AI system — log analysis, pattern recognition, and threat modeling — to identify security gaps. Delivered a responsible-disclosure report with remediation recommendations. | Log analysis, threat modeling, responsible disclosure |

---

## Experience

**Operations Coordinator & System Designer** — Amazon Seller Operations *(Remote, Jan 2024 – Present)*
Automated 485K+ operational touchpoints (order processing, inventory, customer service)
via Python/n8n, cutting manual workload 35% and eliminating fulfillment errors; designed
the workflow system's monitoring and alerting.

**Network Infrastructure Technician** — Universal Studios *(Orlando, FL, Jun 2023 – Nov 2024)*
Hardened network segmentation for 500+ endpoint entertainment systems; validated ACLs
that held against lateral movement during an internal pentest.

---

## Education & Certifications

- **A.S., Cybersecurity and Network Engineering Technology** — Valencia College *(expected Summer 2026)*
- **CompTIA Security+** — in progress *(exam scheduled Summer 2026)*

**Languages:** English · Spanish · Portuguese

---

<div align="center">

📫 Reach me at **Jonth.career@pm.me**

</div>
