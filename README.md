# 👋 Christopher M. Huffstetler

**Application Security Engineer** | Tampa, FL | U.S. Army Veteran

[![Focus](https://img.shields.io/badge/focus-Application_Security-blue)](https://owasp.org)
[![Offense](https://img.shields.io/badge/offense-pentesting-red)](https://owasp.org/www-project-web-security-testing-guide/)
[![FedRAMP](https://img.shields.io/badge/compliance-FedRAMP-green)](https://www.fedramp.gov)
[![HIPAA](https://img.shields.io/badge/compliance-HIPAA-green)](https://www.hhs.gov/hipaa/index.html)
[![Python](https://img.shields.io/badge/code-Python-yellow)](https://www.python.org)

7 years in cybersecurity, currently building and breaking AI agent systems. I spend most of my time on web/API penetration testing, secure SDLC automation, and making agentic AI deployments less terrifying.

## What I work on

- Web application and API penetration testing (Burp Suite Pro, OWASP ZAP, Fortify WebInspect)
- SAST / DAST / SCA pipelines (Checkmarx, Veracode, Snyk) and CI/CD security automation
- FedRAMP and HIPAA environments: NIST SP 800-53 controls, POA&M management
- Cloud and container security: AWS, Azure DevOps, Wiz, Prisma Cloud (CSPM, container scanning)
- Python tooling for vulnerability triage and reporting automation

## Featured project

- **[purple-swarm-lab](https://github.com/BLuef0x27/purple-swarm-lab)**: two AI agent swarms, red and blue, fighting in a fully local, air-gapped Docker arena. Ollama models, separate Qdrant vector stores (no cross-team leakage), Splunk telemetry, and MITRE ATT&CK coverage scoring. Built for $0.

## Security tooling

Original tools I built, each with tests, CI, and docs:

- **[secrets-scanner](https://github.com/BLuef0x27/secrets-scanner)** (Go): hardcoded secret detection across code and git history, provider patterns plus entropy heuristics, SARIF output wired for GitHub Code Scanning, ships as a GitHub Action.
- **[sbom-tool](https://github.com/BLuef0x27/sbom-tool)** (Go): CycloneDX 1.5 / SPDX 2.3 SBOM generation from Go, Python, and Node manifests with OSV.dev vulnerability matching.
- **[prompt-injection-firewall](https://github.com/BLuef0x27/prompt-injection-firewall)** (Python): OWASP LLM01:2025 mitigation layer: Unicode canonicalization, nonce fencing, 11 detection rules, and a secret egress guard with policy-driven actions.
- **[token-abuse-playground](https://github.com/BLuef0x27/token-abuse-playground)** (FastAPI): deliberately vulnerable JWT/OAuth/session lab, 15 challenges each with a working attack PoC and the secure-mode fix.
- **[cloud-compliance-dashboard](https://github.com/BLuef0x27/cloud-compliance-dashboard)** (Go): AWS compliance checks (CIS AWS, SOC2, HIPAA mappings) with drift detection, REST API, and a zero-build dashboard.
- **[api-security-scanner](https://github.com/BLuef0x27/api-security-scanner)** (Python): OpenAPI-driven REST API scanner with BOLA, broken auth, mass assignment, and exposure probes mapped to the OWASP API Top 10.

## Certifications

- ACPT (Altered Security Certified Penetration Tester)
- CCSK v5 (Cloud Security Alliance)
- CAP and CNSP (The SecOps Group)
- Python Programming (Google)
- AI Fundamentals with Capstone (IBM)
- GenAI Adversarial Arsenal Training (Mozilla Workshop)
- COMSEC/Crypto and FACT (U.S. Dept of State)

## Community

- Senior Staff, Pros vs Joes CTF (BSides Las Vegas, NYC, Delaware)
- Speaker, HackSpaceCon: vehicle Bluetooth data privacy
- DEF CON community volunteer, BSides Tampa volunteer
- InfraGard member, CISA/DHS I&A briefing participant

## Currently

- BAS Cybersecurity Management, Pasco-Hernando State College (expected 2028)
- Pursuing CRTO (Zero Point Security)
- Open to Application Security roles: Tampa, FL or remote

## Off the clock

Astronomy, Legos, and an ever-growing collection of forked security tools.

## Connect

- [LinkedIn](https://linkedin.com/in/b3773r-f0r-7h3-fu7ur3)
