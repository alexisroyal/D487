# Chapter 4 Study Guide – *Security Requirements (A2)*

## 📘 Chapter Overview

Chapter 4 focuses on Phase A2 of the Security Development Lifecycle (SDL): **Security Requirements**. This phase aims to define, document, and validate the security requirements that will guide development throughout the SDLC. It builds on the outputs of Phase A1, including risk and threat profiles, legal and compliance data, and privacy concerns.

---

## 🎯 Learning Objectives

- Define the purpose of the **Security Requirements (A2)** phase in the SDL.
- Understand how to derive security requirements from threat profiles and compliance needs.
- Identify sources for security requirements, including standards and regulatory frameworks.
- Document and track requirements using traceability mechanisms.
- Determine testable acceptance criteria for security features.

---

## 🔑 Key Concepts & Definitions

### Security Requirements (A2)
Formal definition of what the system must do to meet:
- Security goals
- Legal and regulatory standards
- Business risk mitigation
- Privacy and operational needs

### Sources of Requirements
- **Internal Policies**: Enterprise security policies and practices.
- **Regulations**: HIPAA, PCI DSS, GDPR, COPPA, etc.
- **Standards**: NIST, ISO/IEC 27001, OWASP ASVS.
- **Threat Profiles**: Derived from risk assessments.
- **Privacy Requirements**: Data classification and retention needs.

### Characteristics of Good Security Requirements
- **Clear and Specific** – No ambiguity.
- **Testable** – Defines how compliance can be verified.
- **Relevant** – Aligned with system purpose and risk profile.
- **Traceable** – Linked to source documents and system features.

---

## ✅ Sample Security Requirements Categories

- Authentication and authorization
- Logging and monitoring
- Data encryption and protection
- Input validation and error handling
- Session management
- Access control
- Audit trails

---

## 📊 Traceability

Traceability ensures that:
- Requirements are implemented and tested.
- Changes are tracked across versions.
- Audits can confirm fulfillment of regulatory mandates.

> Use tools like requirements matrices or issue trackers with tags to map requirements to implementation.

---

## 💬 Key Quotes & Ideas

> “Security requirements should be handled with the same discipline as functional requirements.”

> “Failure to properly document and trace requirements often leads to gaps in coverage and security debt.”

> “A requirement that cannot be tested is not a requirement—it’s a suggestion.”

---

## ❓ Chapter Quick-Check

**Q1:** What phase feeds into Security Requirements (A2)?  
**A:** Security Assessment (A1), including risk and threat profiles.

**Q2:** What frameworks can help define security requirements?  
**A:** OWASP ASVS, NIST SP 800-53, ISO/IEC 27034.

**Q3:** Why is traceability important for security requirements?  
**A:** It allows validation and tracking of implementation and changes.

**Q4:** What kind of requirements should be defined in A2?  
**A:** Functional and non-functional security requirements (e.g., authentication, logging, encryption).

---

## 🧪 Exercises (Reflection & Practice)

- **Security Requirements Drafting**: Create security requirements for a login feature using OWASP ASVS as a guide.
- **Traceability Matrix**: Build a simple matrix linking requirements to risks and regulations.
- **Tool Exploration**: Evaluate tools like Jira, Azure DevOps, or GitHub Projects for tracking security requirements.

---

## 📚 Additional Tip

Store your security requirements in `/docs/security/requirements/` with versioning and tagging to ensure traceability across projects and releases.
