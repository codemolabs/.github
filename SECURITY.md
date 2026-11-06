# Security Policy

Codemo Open Source Labs (COSL) takes security, user privacy, and system safety seriously. We appreciate the responsible disclosure of security vulnerabilities by researchers and contributors.

---

## 1. Supported Scope

This security policy applies to:
- The [codemolabs organization](https://github.com/codemolabs) repositories.
- Official COSL web assets and documentation.

Project-specific repositories may provide additional security scopes and contact endpoints in their own `SECURITY.md` or `docs/SECURITY.md`. If project-specific instructions exist, please follow them in conjunction with this policy.

---

## 2. Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues or public discussions.**

If you discover a security issue or vulnerability in any COSL repository:

1. **Email:** Send a detailed report to **[cosl@codemoteams.org](mailto:cosl@codemoteams.org)**.
2. **Subject line:** Use the format `[SECURITY] <Project Name> - <Brief Description>`.
3. **Report contents:**
   - Name of the affected repository and branch/commit.
   - Detailed description of the vulnerability and its potential impact.
   - Clear step-by-step reproduction instructions or a minimal proof of concept (PoC).
   - Any suggested mitigations or remediation steps, if known.

---

## 3. Vulnerability Response Timeline

- **Initial Acknowledgment:** Within **48 hours** of receiving your report.
- **Triage & Assessment:** Within **5 business days**, validating the issue and determining severity.
- **Resolution & Release:** We aim to release a patch and coordinated advisory as quickly as reasonable, typically within **30 days** depending on complexity.

We ask reporters to maintain confidentiality until a patch has been released and coordinated public disclosure is agreed upon.

---

## 4. Educational & Safe Harbor Principles

COSL materials include educational labs covering software engineering, automation, and security concepts. 
- All security testing and lab exercises must be conducted **only** on systems and targets you own or have explicit written authorization to test.
- Any security research, binary analysis, or malware mechanics studies conducted within COSL laboratories must take place strictly inside isolated, air-gapped sandboxes for defensive learning purposes, conforming to applicable cybercrime statutes and recognized good-faith research frameworks.
- We will not pursue legal action against researchers who discover and report vulnerabilities in good faith in compliance with this policy and without causing disruption, service outages, or data loss.

---

## 5. Compliance Frameworks and Repository Metadata

To maintain a consistent security posture and tracking baseline across all repositories, COSL enforces the `compliance_frameworks` GitHub repository custom property:

| Setting | Configuration | Purpose and Operational Rules |
|:---|:---|:---|
| **Property Name** | `compliance_frameworks` | Standardized tracking metadata for repository security alignment |
| **Property Type** | Multi-select | Permits tagging multiple applicable frameworks where evaluated |
| **Scope** | Required for all repositories | Enforced across all repositories in the organization |
| **Default Value** | `Unassessed` | Safe baseline preventing unsupported or premature compliance claims |
| **Permitted Options** | `PCI DSS`, `SOC 2`, `ISO 27001`, `NIST SP 800-171`, `CMMC`, `Unassessed` | Recognized industry cybersecurity and privacy frameworks |
| **Creation Behavior** | Inherits default automatically | New repositories inherit `Unassessed` without requiring manual claims |
| **Edit Permissions** | Disabled for repository actors | Managed exclusively by authorized organization administrators |

> [!NOTE]
> Values assigned to the `compliance_frameworks` property represent internal tracking metadata. They do not constitute formal third-party audit claims, legal warranties, or regulatory compliance certifications.

---

Thank you for helping keep the COSL community and our open-source software safe!

