# Chapter 7 Study Guide – *Security Testing (A5)*

## 📘 Chapter Overview

Chapter 7 explores Phase A5 of the Security Development Lifecycle (SDL): **Security Testing**. This phase involves validating the implementation of security requirements through a variety of testing methods. It emphasizes the use of automated and manual techniques to uncover vulnerabilities and ensure secure behavior in deployed systems.

---

## 🎯 Learning Objectives

- Understand the objectives and scope of the **Security Testing (A5)** phase.
- Differentiate between testing types: static, dynamic, interactive, and manual.
- Learn how to conduct effective penetration testing and code reviews.
- Integrate testing into the CI/CD pipeline.
- Use results to feed back into design and development processes.

---

## 🔑 Key Concepts & Definitions

### Security Testing (A5)
A validation process using both automated tools and manual techniques to:
- Uncover security vulnerabilities
- Ensure compliance with requirements
- Validate secure behavior of the software

### Types of Security Testing
- **Static Testing (SAST)**: Analyzes source code without running it.
- **Dynamic Testing (DAST)**: Analyzes running applications in real-time.
- **Interactive Testing (IAST)**: Combines SAST and DAST with runtime insights.
- **Manual Testing**: Code reviews, penetration testing, threat validation.

### Penetration Testing
Simulates real-world attacks to:
- Identify exploitable vulnerabilities
- Test application logic and access control
- Assess incident detection and response

---

## ✅ Test Planning & Execution

- Define scope, goals, and timing of tests.
- Include test cases for authentication, session handling, access controls, and input validation.
- Test third-party libraries and APIs.
- Track and remediate findings using issue tracking systems.

> Security testing should begin early and continue through development and into production.

---

## 🧰 Tools & Techniques

- **Static Tools**: Fortify, CodeQL, SonarQube
- **Dynamic Tools**: OWASP ZAP, Burp Suite, Postman
- **Interactive Tools**: Contrast Security, Seeker
- **Manual**: OWASP Testing Guide, checklists, pair review

---

## 💬 Key Quotes & Ideas

> “Testing is not just about finding bugs—it’s about verifying that the software behaves securely.”

> “Security testing must be continuous and evolve with the application.”

> “No tool can replace the human judgment of a well-performed manual review.”

---

## ❓ Chapter Quick-Check

**Q1:** What type of testing involves evaluating a running application?  
**A:** Dynamic Application Security Testing (DAST).

**Q2:** What is the purpose of a penetration test?  
**A:** To simulate an attack and identify exploitable security weaknesses.

**Q3:** Why integrate testing into the CI/CD pipeline?  
**A:** To detect and address vulnerabilities continuously and automatically.

**Q4:** What role does manual testing still play?  
**A:** It provides context-sensitive validation and catches logic flaws tools may miss.

---

## 🧪 Exercises (Reflection & Practice)

- **Tool Selection**: Choose and compare 2 SAST and 2 DAST tools based on your tech stack.
- **Test Planning**: Draft a basic security test plan for a RESTful API.
- **Bug Report Review**: Analyze a historical CVE or bug bounty report and identify what testing failed to catch the issue.

---

## 📚 Additional Tip

Keep a `/testing/security/` folder in your repository with test cases, scan results (sanitized), and remediation logs to support continuous security testing and audit readiness.
