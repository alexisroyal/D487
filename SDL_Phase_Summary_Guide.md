# 📘 Full SDL Phase Summary – *Practical Core Software Security*

This guide summarizes all **Security Development Lifecycle (SDL)** phases (A1–A7) based on the book *Practical Core Software Security*. It is formatted for GitHub-style repositories and includes core goals, practices, and artifacts for each phase.

---

## ✅ SDL Phase Overview

| Phase | Title                         | Purpose                                                                 |
|-------|-------------------------------|-------------------------------------------------------------------------|
| A1    | Security Assessment           | Early engagement, define risk and threat profiles, begin PIA           |
| A2    | Security Requirements         | Define and document testable security requirements                     |
| A3    | Secure Design                 | Integrate security into architecture; threat modeling and attack surface |
| A4    | Secure Coding                 | Implement with secure coding practices, tools, and standards           |
| A5    | Security Testing              | Validate security controls via automated/manual testing                |
| A6    | Security Verification         | Final validation, risk closure, and readiness for release              |
| A7    | Security Release & Response   | Secure release, monitoring, and incident response planning             |

---

## 🔐 A1: Security Assessment

- **Goals**: Identify security risks early, initiate threat profiles and PIA
- **Activities**:
  - Discovery meeting
  - Risk and privacy profiling
  - SDL project planning
- **Artifacts**:
  - Risk and threat profiles
  - SDL task map
  - Compliance checklist

---

## 📄 A2: Security Requirements

- **Goals**: Translate risk and compliance into actionable security requirements
- **Activities**:
  - Use frameworks (e.g., OWASP ASVS, ISO/IEC 27001)
  - Align with laws (HIPAA, GDPR, PCI)
- **Artifacts**:
  - Requirements document
  - Traceability matrix
  - Test criteria

---

## 🏗️ A3: Secure Design

- **Goals**: Design security into system architecture
- **Activities**:
  - Threat modeling (STRIDE, DREAD, PASTA)
  - Use secure design principles
  - Reduce attack surface
- **Artifacts**:
  - Data flow diagrams (DFDs)
  - Threat model docs
  - Design review reports

---

## 💻 A4: Secure Coding

- **Goals**: Write secure, standards-compliant, low-risk code
- **Activities**:
  - Apply OWASP, SEI CERT guidelines
  - Use vetted libraries and APIs
  - Perform static code analysis
- **Artifacts**:
  - Coding standards
  - Linter/SAST results
  - Code review logs

---

## 🔍 A5: Security Testing

- **Goals**: Discover vulnerabilities and validate controls
- **Activities**:
  - SAST, DAST, IAST tools
  - Penetration testing
  - Manual reviews
- **Artifacts**:
  - Test plans and results
  - Bug/issue tracker
  - Security test reports

---

## 🧾 A6: Security Verification

- **Goals**: Ensure all threats are mitigated, ready for release
- **Activities**:
  - Final review of requirements
  - Threat model verification
  - Security sign-off
- **Artifacts**:
  - Verification checklist
  - Updated threat model
  - Compliance and audit docs

---

## 🚨 A7: Security Release & Response

- **Goals**: Release securely, monitor, and respond to incidents
- **Activities**:
  - Validate production readiness
  - Prepare incident response plan
  - Monitor and patch
- **Artifacts**:
  - IR plan
  - Vulnerability disclosure policy
  - Release notes and configs

---

## 🔁 Final Tips

- Store each phase’s artifacts in project-specific folders (`/security/`, `/docs/security/`)
- Align SDL phases to your SDLC model (Agile, Waterfall, DevOps)
- Continuously improve by analyzing incidents and updating threat models

> “Security is not a phase—it is a mindset embedded across the lifecycle.”

