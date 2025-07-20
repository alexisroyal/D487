# Chapter 5 Study Guide – *Secure Design (A3)*

## 📘 Chapter Overview

Chapter 5 explores Phase A3 of the Security Development Lifecycle (SDL): **Secure Design**. This phase focuses on incorporating security principles into software architecture and design. It emphasizes threat modeling, attack surface reduction, and secure design patterns, all of which guide teams in proactively identifying and mitigating risks before implementation.

---

## 🎯 Learning Objectives

- Understand the goals and components of the **Secure Design (A3)** phase.
- Learn how to perform and document **threat modeling**.
- Apply **secure design principles** to system architecture.
- Recognize and reduce the system's **attack surface**.
- Use **design reviews** to verify security integration early in the SDLC.

---

## 🔑 Key Concepts & Definitions

### Secure Design (A3)
The SDL phase where system architecture is reviewed and aligned with:
- Threat models
- Security objectives
- Design principles and patterns
- Risk mitigation plans

### Threat Modeling
A structured approach to identifying and evaluating:
- Threats
- Attack vectors
- Weaknesses
- Countermeasures

> Common models: STRIDE, DREAD, PASTA

### Secure Design Principles
- **Least Privilege** – Limit access rights for users and processes.
- **Defense in Depth** – Layered security controls.
- **Fail Securely** – Fail in a safe manner (e.g., default deny).
- **Economy of Mechanism** – Keep designs simple and small.
- **Separation of Duties** – Spread privileges across roles.
- **Complete Mediation** – Every access to every object must be checked.

### Attack Surface Reduction
- Identify exposed interfaces (APIs, ports, endpoints)
- Eliminate unnecessary services or permissions
- Harden default configurations

---

## ✅ Secure Design Review Elements

- Architectural diagrams with security annotations
- Data flow diagrams (DFDs)
- Threat model documentation
- Known attack patterns and mitigations
- Assumptions and limitations

---

## 📊 Threat Modeling Tips

- Start early (during design)
- Collaborate with cross-functional teams
- Focus on what could go wrong and how to fix it
- Revisit models as design evolves

---

## 💬 Key Quotes & Ideas

> “A flaw in the design is often more devastating than a bug in the code.”

> “Threat modeling is not a one-time event—it’s a continuous process.”

> “Attack surface reduction is one of the most effective ways to limit risk exposure.”

---

## ❓ Chapter Quick-Check

**Q1:** What is the purpose of threat modeling?  
**A:** To identify and prioritize threats and define mitigations before implementation.

**Q2:** What principle supports the idea of checking access every time?  
**A:** Complete Mediation.

**Q3:** What helps reduce the system’s attack surface?  
**A:** Disabling unused services, limiting privileges, and minimizing exposed interfaces.

**Q4:** When should threat modeling occur?  
**A:** During the design phase and updated as changes occur.

---

## 🧪 Exercises (Reflection & Practice)

- **Design Threat Model**: Create a DFD and perform a STRIDE-based threat model for a file upload service.
- **Secure Design Patterns**: Choose 2 design principles and apply them to a login system architecture.
- **Review Practice**: Conduct a peer design review of a sample application with security in mind.

---

## 📚 Additional Tip

Store architectural diagrams, threat models, and review findings in a `/design/security/` folder in your GitHub repo to promote visibility and future iteration.
