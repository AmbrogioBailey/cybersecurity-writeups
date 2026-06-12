# TryHackMe — SOC Fundamentals

**Platform:** TryHackMe  
**Category:** Security Operations  
**Topic:** SOC Structure & SIEM Analysis

---

## What Is a SOC?

A Security Operations Center (SOC) is a team of security professionals responsible for monitoring, detecting, and responding to threats against an organization's systems and network. The SOC operates through a structured escalation hierarchy, with each level handling incidents based on their complexity.

---

## SOC Team Structure

- **SOC Analyst Level 1** — The first responders. When an alert is triggered, L1 analysts are the first to be notified. They triage the alert and determine whether it requires further investigation.
- **SOC Analyst Level 2** — If an incident is too complex for L1 to resolve, it gets escalated here for deeper investigation.
- **SOC Analyst Level 3** — Handles the most advanced and critical incidents that require expert-level analysis.
- **Security Engineer** — Once an incident is fully understood, the Security Engineer builds and implements the solution to address it.
- **SOC Manager** — Oversees the entire SOC operation and reports findings up to the Chief Information Security Officer (CISO).

This escalation structure ensures that every incident gets the right level of attention without overwhelming senior analysts with routine alerts.

---

## What I Did — SIEM Analysis

In this room's hands-on lab, I used a SIEM system to investigate a real-world style security alert.

**SIEM** stands for **Security Information and Event Management**. It matters because it gives analysts a centralized way to detect and investigate the different dimensions of any alert:

- **Who** — the hostname identified the machine involved in the incident
- **When** — the timestamp validated exactly when the incident occurred
- **Where** — the destination IP address (10.0.0.3) identified where the attack was directed

By correlating these three data points inside the SIEM, I was able to piece together a complete picture of the alert — which is exactly what a real SOC Level 1 analyst does before deciding whether to escalate.

---

## Key Takeaway

SOC work isn't just about detecting threats — it's about asking the right questions: who, what, when, and where. SIEM systems are the tool that makes answering those questions possible at scale.

---

*Write-up by Ambrogio Shelton-Bailey | [GitHub](https://github.com/AmbrogioBailey) | [LinkedIn](https://linkedin.com/in/ambrogiobailey)*
