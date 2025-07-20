# 🛡️ Threat Modeling Frameworks Study Guide

This guide covers major threat modeling frameworks including **STRIDE**, **DREAD**, **PASTA**, and supporting models like **LINDDUN** and **Kill Chain**. These models help identify, categorize, and prioritize security threats during the design and analysis phases of software development.

---

## 🔷 STRIDE – Microsoft’s Threat Categorization Model

**S**poofing  
**T**ampering  
**R**epudiation  
**I**nformation Disclosure  
**D**enial of Service  
**E**levation of Privilege

| Threat             | Description                                              | Example                            |
|--------------------|----------------------------------------------------------|------------------------------------|
| Spoofing           | Pretending to be someone else                            | Using stolen credentials           |
| Tampering          | Modifying data or code                                   | Changing a config file             |
| Repudiation        | Denying actions without auditability                     | User denies transaction without logs |
| Information Disclosure | Exposing sensitive information                    | Leaking PII via logs               |
| Denial of Service  | Disrupting service availability                          | Flooding server with traffic       |
| Elevation of Privilege | Gaining unauthorized rights                        | Normal user gaining admin access   |

---

## 🔷 DREAD – Risk Assessment Model

**D**amage Potential  
**R**eproducibility  
**E**xploitability  
**A**ffected Users  
**D**iscoverability

Each threat is scored (0–10), and total scores help prioritize mitigation.

| Category        | Sample Question                                      |
|----------------|------------------------------------------------------|
| Damage          | How severe is the impact if exploited?              |
| Reproducibility | Can the attack be easily repeated?                  |
| Exploitability  | How easy is it to launch the attack?                |
| Affected Users  | How many users are impacted?                        |
| Discoverability | How easy is it to find the vulnerability?           |

> **Risk Score = (D + R + E + A + D) / 5**

---

## 🔷 PASTA – Attack Simulation Methodology

**P**rocess for  
**A**ttack  
**S**imulation and  
**T**hreat  
**A**nalysis

A 7-step risk-centric methodology focused on simulating real-world attacks.

1. **Define Objectives** – Business and technical impact
2. **Define Technical Scope** – Architecture, components
3. **Application Decomposition** – DFDs, trust boundaries
4. **Threat Analysis** – Identify attacker profiles and capabilities
5. **Vulnerability Analysis** – Weaknesses in architecture or design
6. **Attack Simulation** – Simulate how threats could exploit vulnerabilities
7. **Risk & Impact Analysis** – Map to business risks, prioritize mitigation

---

## 🔷 LINDDUN – Privacy-Centric Threat Modeling

**L**inkability  
**I**dentifiability  
**N**on-repudiation  
**D**etectability  
**D**isclosure of Information  
**U**nawareness  
**N**on-compliance

Used for identifying privacy threats in systems dealing with personal data.

---

## 🔷 MITRE ATT&CK / Kill Chain

- **MITRE ATT&CK**: A matrix of attacker behaviors organized by tactics and techniques.
- **Cyber Kill Chain** (Lockheed Martin): A linear attack sequence:
  1. Reconnaissance
  2. Weaponization
  3. Delivery
  4. Exploitation
  5. Installation
  6. Command and Control
  7. Actions on Objectives

> Often used in red teaming and defense alignment.

---

## 🧠 Tips for Using Threat Models

- Start with **STRIDE** for design-time security analysis.
- Use **PASTA** when you need a full attack simulation or business-risk analysis.
- Choose **LINDDUN** for systems processing personal or sensitive data.
- Leverage **MITRE ATT&CK** when building detection or incident response plans.
- Combine models when needed for layered insight.

---

## 📚 Study Practice

- Create a STRIDE threat model for a login system.
- Apply DREAD scoring to threats identified in a mobile app.
- Run a PASTA simulation on a cloud-based file-sharing platform.
- Use LINDDUN on a healthcare app storing patient records.
- Map a recent CVE to the Kill Chain or MITRE ATT&CK framework.

---

## 📁 Suggested Folder Structure (for Projects)

```
/threat-models/
├── stride/
├── pasta/
├── dread/
├── linddun/
├── attack-chain/
```

Include DFDs, threat logs, simulations, and response planning in your repo for traceability.

> “Threat modeling isn’t a checkbox — it’s a strategy for building resilient systems.”

