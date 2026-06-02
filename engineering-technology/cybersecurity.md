---
domain: engineering-technology
subdomain: cybersecurity
title: "Cybersecurity"
description: "The practice of protecting systems, networks, and programs from digital attacks"
created: 2026-06-02
updated: 2026-06-02
tags: [security, cyber, networks, privacy, encryption, threats, defense, ethical-hacking]
prerequisites: [engineering-technology/computer-science]
related: [engineering-technology/computer-science, engineering-technology/software-engineering]
difficulty: intermediate
completeness: comprehensive
---

# Cybersecurity

## Overview

Cybersecurity is the practice of protecting computer systems, networks, programs, and data from unauthorized access, use, disclosure, disruption, modification, or destruction. It encompasses technologies, processes, and practices designed to defend against threats like cyberattacks, data breaches, and malicious actors. As our reliance on digital systems grows, cybersecurity becomes increasingly critical to protecting individuals, organizations, and nations.

## Core Concepts

### Core Security Principles
- **CIA Triad**: Confidentiality, Integrity, Availability — foundational principles
- **Authentication, Authorization, Accounting (AAA)**: Verifying identity, granting permissions, auditing
- **Zero Trust Architecture**: "Never trust, always verify"; continuous validation
- **Defense in Depth**: Multiple layered security controls
- **Least Privilege**: Minimum necessary access rights
- **Separation of Duties**: Critical tasks require multiple individuals

### Threats & Vulnerabilities
- **Malware**: Viruses, worms, Trojans, ransomware, spyware, adware
- **Network Attacks**: DDoS, Man-in-the-Middle, packet sniffing, phishing
- **Social Engineering**: Phishing, spear phishing, whaling, pretexting
- **Exploits & Zero-Days**: Known vulnerabilities, unpatched issues
- **Insider Threats**: Malicious or negligent insiders
- **Advanced Persistent Threats (APTs)**: Targeted, sophisticated, long-term attacks

### Cryptography
- **Symmetric Encryption**: Shared key; AES, DES, Blowfish
- **Asymmetric Encryption**: Key pairs; RSA, ECC, Diffie-Hellman
- **Hash Functions**: SHA-256, MD5 (obsolete), hashing integrity
- **Public Key Infrastructure (PKI)**: Certificates, CAs, trust chains
- **Digital Signatures**: Non-repudiation, integrity verification
- **Quantum Cryptography**: Quantum key distribution, post-quantum crypto

### Network Security
- **Firewalls**: Next-gen firewalls, network security groups, WAFs
- **Intrusion Detection/Prevention**: IDS (detection), IPS (prevention), signature vs anomaly-based
- **VPNs**: Virtual Private Networks, secure tunnels
- **Network Segmentation**: VLANs, microsegmentation, zero trust
- **Secure Protocols**: HTTPS, TLS, SSH, SFTP
- **DNS Security**: DNSSEC, DNS filtering, DNS over HTTPS

### Application Security
- **Secure Coding**: OWASP Top 10, secure design patterns, input validation
- **Web Application Security**: XSS, CSRF, SQLi, insecure deserialization
- **Mobile App Security**: iOS/Android best practices, app vetting, runtime protection
- **API Security**: OAuth 2.0, OpenID Connect, API keys, rate limiting
- **Software Supply Chain Security**: SBOMs, supply chain attacks, dependency scanning
- **Security Testing**: Penetration testing, static analysis, dynamic analysis, fuzzing

### Identity & Access Management
- **Password Security**: Complexity, hashing, password managers, phishing resistance
- **Multi-Factor Authentication (MFA)**: Something you have, know, are
- **Single Sign-On (SSO)**: SAML, OAuth 2.0, OIDC
- **Identity Providers (IdPs)**: Azure AD, Okta, Ping Identity
- **Privileged Access Management (PAM)**: Just-in-time, vaulting, elevation
- **Biometrics**: Fingerprint, facial, retina, iris, voice recognition

### Cloud Security
- **Cloud Shared Responsibility Model**: Provider vs customer responsibilities
- **Identity in Cloud**: IAM roles, policies, RBAC, temporary credentials
- **Data Protection**: Encryption at rest/in transit, secrets management, key management
- **Cloud Security Posture Management (CSPM)**: Misconfiguration detection, compliance
- **Serverless Security**: Function-level isolation, least privilege, observability
- **Container Security**: Image scanning, network policies, runtime protection

### Data Security & Privacy
- **Data Classification**: Public, internal, confidential, restricted
- **Encryption at Rest & in Transit**: TLS, AES, key management
- **Data Loss Prevention (DLP)**: Content inspection, exfiltration prevention
- **Privacy Regulations**: GDPR, CCPA, HIPAA, PIPEDA, LGPD
- **Data Breach Response**: Notification, containment, investigation, remediation
- **Anonymization & Pseudonymization**: K-anonymity, differential privacy

### Security Operations
- **SIEM (Security Information & Event Management)**: Log aggregation, correlation, alerting
- **SOC (Security Operations Center)**: 24/7 monitoring, incident response
- **Incident Response (IR)**: Identification, containment, eradication, recovery
- **Threat Intelligence**: IOCs, threat feeds, TTPs, threat hunting
- **Vulnerability Management**: Scanning, assessment, prioritization, patching
- **Forensics & Investigation**: Digital forensics, evidence collection, analysis

### Security Policies & Compliance
- **Regulations & Standards**: HIPAA, PCI-DSS, FedRAMP, SOC 2, NIST CSF
- **Information Security Policies**: Acceptable use, data handling, incident response
- **Risk Management**: Risk assessment, risk appetite, treatment (avoid, mitigate, transfer, accept)
- **Audit & Assessment**: Internal vs external audits, penetration tests, compliance checks
- **Business Continuity/Disaster Recovery (BCDR)**: Resilience, recovery time objectives (RTO), recovery point objectives (RPO)

### Ethical Hacking & Penetration Testing
- **Methodologies**: OSSTMM, OWASP Testing Guide, PTES
- **Types of Testing**: White, gray, black box; internal/external
- **Reconnaissance**: Passive/active, footprinting, scanning
- **Exploitation**: Vulnerability exploitation, social engineering, lateral movement
- **Post-Exploitation**: Maintaining access, privilege escalation, exfiltration
- **Reporting**: Vulnerability assessment, recommendations, impact analysis

### Cybersecurity Laws & Ethics
- **Computer Fraud and Abuse Act (CFAA)**: US law on unauthorized access
- **Cybersecurity Act**: EU legislation, NIS 2 directive
- **State-Sponsored Hacking**: International law, norms, attribution challenges
- **Ethical Hacking Ethics**: Permission, disclosure, do no harm
- **Professional Codes**: (ISC)², ISACA, OWASP ethics
- **Responsible Disclosure**: Bug bounty programs, coordinated disclosure

### Specialized Cybersecurity Domains
- **Industrial Control Systems (ICS)/OT Security**: SCADA, PLCs, operational technology
- **Critical Infrastructure**: Power grids, transportation, water systems, healthcare
- **Maritime & Aviation Cybersecurity**: Vessel systems, air traffic control, IoT in transit
- **Medical Device Security**: FDA guidance, patient safety, connected health
- **Automotive Cybersecurity**: CAN bus, infotainment, ADAS, autonomous vehicles
- **Cryptocurrency & Blockchain Security**: Wallets, exchanges, DeFi, consensus security

## Key Theories

| Theory | Key Figure | Core Idea |
|--------|-----------|-----------|
| CIA Triad | Various | Security consists of confidentiality, integrity, and availability |
| Zero Trust | John Kindervag | "Never trust, always verify"; no implicit trust in any entity |
| Kill Chain | Lockheed Martin | Stages of cyberattack: reconnaissance, weaponization, delivery, exploitation, installation, command and control, actions on objectives |
| Defense in Depth | Various | Multiple layered defenses so failure of one doesn't compromise all |
| Consequence Causation | Various | Incidents result from complex interacting factors, not single causes |
| Principle of Least Privilege | Various | Subjects should only have necessary access |

## Important Figures

- **Shafi Goldwasser & Silvio Micali**: Probabilistic encryption, zero-knowledge proofs
- **Ron Rivest, Adi Shamir, Leonard Adleman (RSA)**: RSA public-key cryptography
- **Whitfield Diffie & Martin Hellman**: Public-key cryptography breakthrough
- **Bruce Schneier**: Applied cryptography, security culture, cryptographer
- **Kevin Mitnick**: Former hacker turned security consultant
- **Bruce Schneier**: Security pragmatist, author, commentator
- **Dan Kaminsky**: DNS security researcher
- **Dawn Song**: Security research, AI and security, UC Berkeley
- **Ross Anderson**: Security engineering, economics of information security
- **Jennifer Granick**: Cybersecurity and civil liberties lawyer

## Frontiers

- **AI & Machine Learning for Security**: Anomaly detection, predictive threat intelligence, automated response
- **Quantum-Safe Cryptography**: Preparing for post-quantum encryption standards
- **Zero Trust at Scale**: Extending zero trust to distributed, hybrid, multi-cloud environments
- **Supply Chain Security**: Defending software supply chains against modern threats
- **Sovereign Cybersecurity**: Nations building cyber capabilities, norms, deterrence
- **Cybersecurity of Autonomous Systems**: Self-driving cars, drones, robotics security
- **Cybersecurity in Metaverse & Virtual Worlds**: Identity, virtual assets, digital property rights
- **Privacy-Enhancing Technologies (PETs)**: Homomorphic encryption, zero-knowledge proofs, differential privacy
- **Decentralized Identity (DID)**: Self-sovereign identity, verifiable credentials

## Applications

- **Enterprise Security**: Protecting organizations from cyber threats
- **Government & National Security**: Critical infrastructure, defense, intelligence
- **Financial Services**: Banking, payment systems, fraud prevention
- **Healthcare Security**: Protecting patient data, medical devices, EHR systems
- **Cloud Security**: Securing cloud infrastructure, applications, and data
- **Endpoint Security**: Antivirus, EDR, XDR, device security
- **Mobile Security**: Protecting smartphones, tablets, apps, and mobile data
- **IoT Security**: Internet of Things, embedded systems, connected devices

## Classic Works

- **"Applied Cryptography"** by Bruce Schneier — Protocols, algorithms, and source code
- **"The Art of Deception"** by Kevin Mitnick — Stories of social engineering
- **"The Hacker Crackdown"** by Bruce Sterling — History of hacking and counterculture
- **"The Cuckoo's Egg"** by Clifford Stoll — First account of tracking a hacker
- **"Threat Modeling"** by Adam Shostack — Designing security into systems
- **"Security Engineering"** by Ross Anderson — Comprehensive guide to building secure systems

## See Also

- [Computer Science](computer-science.md) — Computing fundamentals
- [Software Engineering](software-engineering.md) — Secure development practices
- [Data Science](data-science.md) — AI/ML security, privacy-preserving ML

