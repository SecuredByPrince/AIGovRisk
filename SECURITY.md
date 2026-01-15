# Security Policy

## 📌 Overview

Security is a core principle of **AIGovRisk**.

This project is designed to support **AI governance, risk management, and compliance**, and therefore follows **secure-by-design** and **responsible disclosure** principles.

We take security vulnerabilities seriously and appreciate responsible reporting from the community.

---

## 🔐 Security Principles

AIGovRisk is developed with the following security principles in mind:

- **Least Privilege** – Access is restricted to what is strictly necessary  
- **Defense in Depth** – Multiple layers of security controls  
- **Explainable Risk Logic** – Transparent, auditable decision-making  
- **Secure Defaults** – Conservative configurations by default  
- **Data Minimization** – Only required data is collected and stored  

---

## 📢 Reporting a Vulnerability

If you discover a security vulnerability, please **do not open a public GitHub issue**.

### ✅ Responsible Disclosure

Please report vulnerabilities by emailing:

📧 **security@aigovrisk.com** *(placeholder — update when live)*

Include:
- A clear description of the vulnerability
- Steps to reproduce (if applicable)
- Potential impact
- Any relevant screenshots or logs (sanitized)

We aim to acknowledge reports within **72 hours**.

---

## 🚫 Scope of Security Issues

### ✔️ In Scope
- Authentication and authorization issues
- Access control flaws
- API security vulnerabilities
- Data exposure or leakage
- Injection or input validation issues
- Misconfiguration risks
- Logic flaws affecting risk scoring or governance output

### ❌ Out of Scope
- Social engineering attacks
- Denial-of-service (DoS) attacks
- Physical attacks
- Issues in third-party dependencies (report upstream)

---

## 🔍 Security Testing & Reviews

Security practices include:

- Secure coding practices
- Dependency review
- Input validation
- Manual code review
- Risk logic validation

Automated security scanning may be added in later phases.

---

## 🧠 AI & Governance-Specific Security Considerations

Given the nature of AIGovRisk:

- Risk scoring logic must remain **explainable**
- Governance outputs must not be misleading or overstated
- The platform does **not** replace legal, regulatory, or certification authorities
- AI governance recommendations are **decision-support**, not guarantees

---

## 🔒 Data Protection & Privacy

- No sensitive production data should be committed to the repository
- Test data must be anonymized
- Secrets must not be hardcoded
- Environment variables should be used for credentials

---

## ⚠️ Supported Versions

AIGovRisk is currently in **active development (MVP stage)**.

Security fixes are applied to:
- `main` branch (current development)

Older commits or forks may not receive security updates.

---

## 🤝 Coordinated Disclosure

We request that reporters:
- Allow reasonable time for remediation
- Avoid public disclosure until a fix is available
- Coordinate with the project maintainers

We believe coordinated disclosure benefits both users and contributors.

---

## 📄 Disclaimer

AIGovRisk is an **open-source research and governance support tool**.

It does **not** provide:
- Legal advice
- Regulatory certification
- Compliance guarantees

Organizations remain responsible for their own governance decisions.

---

## 🙏 Acknowledgements

We thank the security community for helping improve the safety and reliability of AIGovRisk.

Responsible disclosure helps everyone.

---

*Maintained by the AIGovRisk project team*
