# Chapter 1 Study Guide – *Introduction to Software Security*

## 📘 Chapter Overview

This chapter introduces the fundamental importance of **software security** and sets the stage for why building security into the Software Development Life Cycle (SDLC) is critical. It emphasizes the distinction between secure and quality code, introduces the **CIA triad**, and outlines early-phase practices like threat modeling and attack surface analysis.

---

## 🎯 Learning Objectives

- Explain why software security must be integrated from the beginning of development.
- Distinguish between **software security** and **application security**.
- Understand the difference between **secure code** and **quality code**.
- Describe the **CIA triad**: Confidentiality, Integrity, and Availability.
- Understand the role of **threat modeling** and **attack surface analysis**.
- Realize the cost and impact of fixing security issues later in the SDLC.

---

## 🔑 Key Concepts & Definitions

### Software Security vs. Application Security
- **Software Security**: Involves building security into the design and development of software.
- **Application Security**: Involves protecting software after it has been deployed (e.g., WAFs, firewalls).

### Quality Code vs. Secure Code
- **Quality Code**: Reliable, maintainable, and performs well.
- **Secure Code**: Designed to resist exploitation and protect against threats.
> _A program can be high-quality but still insecure._

### CIA Triad
- **Confidentiality**: Preventing unauthorized access.
- **Integrity**: Preventing unauthorized modification.
- **Availability**: Ensuring data and services are accessible when needed.

### Threat Modeling
- A proactive process for identifying and evaluating potential threats.
- Helps mitigate risks before code is written.

### Cost of Fixing Defects
- Fixing security issues after deployment can cost **50–200x** more than addressing them during early phases like requirements or design.

---

## 💬 Key Quotes & Ideas

> “Security must be built in from the very start.”

> “Secure code is not necessarily quality code, and vice versa.”

> “Threat modeling is the most time-consuming and misunderstood part of the SDL — but also the most critical.”

---

## ❓ Chapter Quick-Check

**Q1:** What are the three goals of SDL?  
**A:** Confidentiality, Integrity, and Availability (CIA triad).

**Q2:** Which activity is most effective before writing any code?  
**A:** Threat modeling.

**Q3:** Defective software is primarily a:  
**A:** Software development and engineering problem.

**Q4:** Fixing flaws post-release can be how much more expensive?  
**A:** Up to 100 times more expensive.

---

## 🧪 Exercises (Reflection & Practice)

- Visit the [CSIS Cyber Incidents](https://www.csis.org/programs/strategic-technologies-program/significant-cyber-incidents) page. Identify which SDL activities might have prevented listed incidents.
- Reflect: How does your team or organization currently integrate security into development?
- Pitch Exercise: How would you justify training developers in secure coding to leadership?

---

## 📚 Additional Tip

Start a `security/early-assessments/` folder in your repo to store risk analysis, threat models, and security-related planning docs to ensure traceability and early visibility.
