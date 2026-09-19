# Cyber Security Governance, Threat Modeling & Incident Response

A group project for the Cyber Security course, MSc Computer and System Science, Stockholm University — covering national cybersecurity policy, organizational security policies, threat modeling, penetration testing, and incident response.

> 🤝 **Group project** — done with Mohammad Kamrul Hasan, Ammar Shareiyat, and Ankit Gautam. Work was split evenly across all four cases.

## 📖 What this covers

### Main Assignment — National Cybersecurity Strategy (NCSS)
A full national cybersecurity strategy for a fictional country ("Cyberia"), built on real-world frameworks: the ITU Global Cybersecurity Agenda, the "Guide to Developing a National Cybersecurity Strategy," ISO/IEC 27000, and the UK's National Cyber Security Strategy 2016–2021. Covers three strategic pillars: **Legal Measures** (cybercrime legislation, government legal authority), **Technical and Procedural Measures** (national cybersecurity framework based on ISO/IEC 27000, securing government infrastructure, critical information infrastructure protection), and **Organizational Structures** (government's cybersecurity role, national incident management, skills and training).

### Case 1 — Organizational Security Policies
Security policies designed for a cryptocurrency exchange platform, referencing **ISO 27001/27002**:
- **Transaction Policy** — securing buy/sell cryptocurrency transactions with logging and P2PKH cryptographic signing
- **Access Control Policy** — least-privilege enforcement
- **Compliance Policy** — GDPR, Swedish/EU regulation, and ISO 27001 alignment
- **Backup and Restore Policy** — the 3-2-1 backup rule, encrypted backups (including private key storage for customer crypto wallets), hash-verified integrity testing, and remote/physical protection

### Case 2 — Threat Modeling (STRIDE)
A STRIDE-based threat model for a fictional media organization ("Radio Sweden"): system decomposition (entry/exit points, assets, external dependencies), followed by threats and countermeasures across all six STRIDE categories — Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, and Elevation of Privilege.

### Case 3 — Penetration Testing
A **NIST SP 800-115**-based penetration test plan for the same organization, covering all four NIST phases (Planning, Discovery, Attack, Reporting). Includes a real vulnerability assessment table referencing actual CVEs against specific infrastructure (Cisco ASA firewalls, Cisco routers, HP switches, Windows Server 2016, Solaris), and a security metrics framework (patch management, vulnerability management, antivirus coverage, recovery time, code security metrics).

### Case 4 — Cyber Security Incident Response
A full incident response walkthrough based on **NIST SP 800-61r2**, analyzing a suspicious after-hours SSH file transfer incident at a fictional organization ("Casino 10-4"). Covers incident classification (insider vs. outsider, policy violation analysis), the full incident response lifecycle (Preparation → Detection & Analysis → Containment/Eradication/Recovery → Post-Incident Activity), incident prioritization, and structured post-incident review questions.

## 🧰 Frameworks & standards used
STRIDE threat modeling, NIST SP 800-115 (Penetration Testing), NIST SP 800-61r2 (Incident Handling), ISO/IEC 27001 & 27002, ITU National Cybersecurity Strategy Guide, GDPR

## 💡 What I learned
End-to-end exposure to cybersecurity from a governance and defensive perspective — writing enforceable security policy, systematically modeling threats before they occur (STRIDE), planning and scoping a penetration test against real, CVE-referenced vulnerabilities, and running a structured incident response process from detection through to post-incident lessons learned. This connected policy-level thinking (compliance, legal frameworks, organizational responsibility) with the technical reality of how systems actually get attacked and defended.

---
*Group project — MSc Computer and System Science, Stockholm University. Co-authored with Mohammad Kamrul Hasan, Ammar Shareiyat, and Ankit Gautam.*
