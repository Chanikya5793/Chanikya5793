# Chanakya Thotakura

**Security Software Engineer | Python automation · detection engineering · E2EE · cloud security**

I build practical security controls across customer-facing applications, endpoint telemetry, and cloud infrastructure. My work includes a public Python detection-as-code platform, per-device Signal Protocol encryption for a financial collaboration product, least-privilege Firebase authorization, secure notification delivery, and API-driven infrastructure automation.

I am a Google Cloud Associate Cloud Engineer and an M.S. Applied Computer Science candidate at Northwest Missouri State University (GPA: 3.7/4.0).

[LinkedIn](https://www.linkedin.com/in/chanikya6163) · [Email](mailto:chanikya1@icloud.com) · Maryville, Missouri

---

## Security Engineering Work

### [ControlForge Security](https://github.com/Chanikya5793/controlforge-security) — Endpoint assurance and detection automation

**Python · FastAPI · Sigma-style YAML · SQLite · Docker · GitHub Actions**

- Validates installation, process state, and heartbeat freshness for configurable endpoint agents, with example definitions for CrowdStrike Falcon, Microsoft Defender for Endpoint, and SentinelOne.
- Evaluates version-controlled detection rules and stateful identity/insider-risk signals for encoded PowerShell, phishing indicators, unauthorized privilege grants, impossible travel, and bulk sensitive-data access.
- Produces explainable, deduplicated alerts through a CLI and REST API; verified by 29 tests at 93% coverage, strict typing, linting, and security static analysis.
- Published as an installable wheel and source distribution in the [v0.1.0 release](https://github.com/Chanikya5793/controlforge-security/releases/tag/v0.1.0).

### [ManaSplit / SplitCircle](https://github.com/Chanikya5793/SplitCircle) — Secure financial collaboration

**React Native · TypeScript · Firebase · Swift · Kotlin · Signal Protocol**

- Engineered fail-closed, per-device end-to-end encryption with identity/prekey lifecycle management, session repair, secure key storage, device revocation, and offline encrypted delivery.
- Designed least-privilege Firebase authorization around authenticated users, group/chat membership, server-owned identity records, and device-scoped claims.
- Built encrypted push-notification previews, token masking/invalidation, remote notification revocation, and regression coverage for encryption and privacy behavior.

### Security Automation & Infrastructure Lab *(private)*

**Python · Shell · Cloudflare API · Docker · Nginx · TLS**

- Automates public-IP monitoring and multi-record Cloudflare DNS updates through REST APIs with structured logging, response validation, and isolated per-record failure handling.
- Operates containerized services behind Nginx with automated TLS renewal, PostgreSQL/Redis, and controlled updates.
- Includes hands-on DNS, WHOIS, traceroute, AES-256, and RSA validation exercises.

---

## Additional Engineering Work

### [GDPProject](https://github.com/Chanikya5793/GDPProject) — Northwest student planning platform

Collaborative graduate project focused on translating student-planning requirements into a maintainable application, explicit data flows, and team-owned delivery.

### [Visu-Net](https://github.com/Chanikya5793/visu-net) — Neural-network visualization

Interactive React and TypeScript application for constructing and inspecting neural-network architectures and training behavior.

---

## Technical Focus

| Area | Technologies and practices |
|---|---|
| Security engineering | Detection-as-code, endpoint assurance, Sigma-style rules, E2EE, IAM/RBAC, device revocation, cryptography, DNS/WHOIS/TLS |
| Automation | Python, FastAPI, Shell, REST APIs, asynchronous processing, structured logging, testing |
| Application engineering | TypeScript/JavaScript, React Native, React, Java, Swift, Kotlin, Firebase |
| Cloud and infrastructure | Google Cloud, Firebase Security Rules, Docker, Nginx, Certbot/Let's Encrypt, Cloudflare, PostgreSQL, Redis |

## Certifications

- Google Cloud Associate Cloud Engineer
- Cisco Introduction to Cybersecurity
- Palo Alto Networks Introduction to Cybersecurity
- Cisco Programming Essentials in Python and C
- HackerRank SQL (Advanced)

## Current Direction

I am interested in security-engineering roles where I can automate defenses, improve detection quality, and protect customer-facing financial systems. I am extending ControlForge toward authenticated vendor adapters, full pySigma interoperability, telemetry metrics, and analyst false-positive feedback loops.
