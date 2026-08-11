# Chanakya Thotakura

**Security-focused software engineer | Python automation · phishing detection · E2EE · cloud security**

I build practical security controls across customer-facing applications, cloud infrastructure, and developer workflows. My work includes per-device Signal Protocol encryption for a financial collaboration product, explainable phishing detection for Gmail, least-privilege Firebase authorization, encrypted notification delivery, and API-driven infrastructure automation.

I am a Google Cloud Associate Cloud Engineer and an M.S. Applied Computer Science candidate at Northwest Missouri State University (GPA: 3.7/4.0, expected August 2027).

[LinkedIn](https://www.linkedin.com/in/chanikya6163) · [Email](mailto:chanikya1@icloud.com) · Maryville, Missouri

---

## Security Engineering Work

### [ManaSplit / SplitCircle](https://github.com/Chanikya5793/SplitCircle) — Secure financial collaboration

**React Native · TypeScript · Firebase · Swift · Kotlin · Signal Protocol**

- Engineered fail-closed, per-device end-to-end encryption with identity/prekey lifecycle management, session repair, secure key storage, device revocation, and offline encrypted delivery.
- Designed least-privilege Firebase authorization around authenticated users, group/chat membership, server-owned identity records, and device-scoped claims.
- Built encrypted push-notification previews, token masking/invalidation, remote notification revocation, and regression coverage for encryption and privacy behavior.

### ChEx — Gmail phishing detection extension *(private security prototype)*

**JavaScript · Chrome Manifest V3 · Gemini**

- Analyzes sender identity, subject, message content, and embedded URLs for urgency/social-engineering language, suspicious TLDs, IP-literal hosts, and credential-themed paths.
- Produces explainable, severity-rated warnings with asynchronous analysis, scan telemetry, retry handling, and a deterministic heuristic fallback.
- Uses Gmail-scoped host access and minimal extension permissions. A sanitized public demonstration is in preparation.

### Security Automation & Infrastructure Lab *(private)*

**Python · Shell · Cloudflare API · Docker · Nginx · TLS**

- Automates public-IP monitoring and multi-record Cloudflare DNS updates through REST APIs with structured logging, response validation, and isolated per-record failure handling.
- Operates containerized services behind Nginx with automated TLS renewal, PostgreSQL/Redis, and controlled updates.
- Includes hands-on DNS, WHOIS, traceroute, AES-256, and RSA validation exercises.

---

## Additional Engineering Work

### [TeluguChatBot](https://github.com/Chanikya5793/TeluguChatBot) — Voice and retrieval assistant

**Python · Gemini · Vertex AI · RAG · MCP · MySQL**

Telugu voice assistant evolved from my AIMERS internship work. It combines speech recognition, intent classification, structured data access, retrieval, function calling, and explicit failure handling.

### [GDPProject](https://github.com/Chanikya5793/GDPProject) — Northwest student planning platform

Collaborative graduate project focused on translating student-planning requirements into a maintainable application, explicit data flows, and team-owned delivery.

### [Visu-Net](https://github.com/Chanikya5793/visu-net) — Neural-network visualization

Interactive React and TypeScript application for constructing and inspecting neural-network architectures and training behavior.

---

## Technical Focus

| Area | Technologies and practices |
|---|---|
| Security engineering | Phishing/email/URL analysis, E2EE, IAM/RBAC, OAuth, device revocation, cryptography, DNS/WHOIS/TLS |
| Automation | Python, Shell, REST APIs, asynchronous processing, structured logging, testing |
| Application engineering | TypeScript/JavaScript, React Native, React, Java, Swift, Kotlin, Firebase |
| Cloud and infrastructure | Google Cloud, Firebase Security Rules, Docker, Nginx, Certbot/Let's Encrypt, Cloudflare, PostgreSQL, Redis |

## Certifications

- Google Cloud Associate Cloud Engineer
- Cisco Introduction to Cybersecurity
- Palo Alto Networks Introduction to Cybersecurity
- Cisco Programming Essentials in Python and C
- HackerRank SQL (Advanced)

## Current Direction

I am interested in security-engineering roles where I can automate defenses, improve detection quality, and protect customer-facing financial systems. My next focused build is a detection-engineering lab covering event normalization, Sigma-style rules, repeatable test fixtures, and false-positive tuning.
