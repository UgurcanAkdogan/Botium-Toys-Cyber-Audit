# Internal Security Audit & Risk Assessment: Botium Toys

> Part of my Google Cybersecurity Professional Certificate portfolio. Botium Toys is a fictional company used in the course scenario.

## Project Overview

This project is an internal security audit for **Botium Toys**, a fictional small U.S. business that sells toys online. The goal was to assess the company's security posture, check compliance with global standards (PCI DSS and GDPR), and give actionable recommendations to reduce the risks I found.

## Audit Objectives

- Evaluate existing security controls against the **NIST Cybersecurity Framework (CSF)**
- Assess compliance with **PCI DSS** (Payment Card Industry Data Security Standard) for credit card processing
- Check adherence to **GDPR** (General Data Protection Regulation) for E.U. customer data
- Identify critical vulnerabilities and prioritize them by impact

## Methodology

- **NIST CSF:** Identify, Protect, Detect, Respond, Recover
- **Compliance checklists:** structured review of regulatory requirements
- **Risk assessment matrix:** scoring risks by likelihood and impact

## Key Findings

| Area | Finding |
| --- | --- |
| **Encryption** | Critical gap: credit card data is stored in plain text |
| **Access control** | "Least privilege" and "separation of duties" are not applied |
| **Disaster recovery** | No formal plan for data recovery or business continuity |
| **Monitoring** | No intrusion detection system (IDS) in place |

## Recommendations

1. Implement **AES-256 encryption** for all sensitive data at rest and in transit.
2. Enforce **multi-factor authentication (MFA)** and the principle of least privilege across all departments.
3. Develop and test a formal **disaster recovery plan (DRP)**.
4. Integrate an **IDS/IPS** solution into the network for real-time threat detection.

## Documentation

- [Scope, goals, and risk assessment report](./Botium_Toys%3A%20Scope_goals_and_risk_assessment_report.pdf)
- [Control categories](./Control_Categories.pdf)
- [Controls and compliance checklist (PCI DSS & GDPR)](./Controls_and_compliance_checklist.pdf)

## Skills Demonstrated

- Security auditing and risk assessment
- Applying NIST CSF, PCI DSS, and GDPR
- Prioritizing risks and writing clear recommendations for stakeholders
