# Botium-Toys-Cyber-Audit
Google Cybersecurity Professional Certificate - Security Audit &amp; Risk Assessment Project
# Internal Security Audit & Risk Assessment: Botium Toys

## Project Overview
This project involves a comprehensive internal security audit for **Botium Toys**, a fictional e-commerce company. The goal was to assess the company's current security posture, evaluate compliance with global standards (PCI DSS & GDPR), and provide actionable recommendations to mitigate identified risks.

## Audit Objectives
- Evaluate existing security controls based on the **NIST Cybersecurity Framework (CSF)**.
- Assess compliance with **PCI DSS** (Payment Card Industry Data Security Standard) for credit card processing.
- Ensure adherence to **GDPR** (General Data Protection Regulation) for E.U. customer data privacy.
- Identify critical vulnerabilities and prioritize them based on their impact.

## Methodology
The audit was conducted using the following frameworks and tools:
- **NIST CSF:** Identify, Protect, Detect, Respond, Recover.
- **Compliance Checklists:** Structured analysis of regulatory requirements.
- **Risk Assessment Matrix:** Scoring risks based on likelihood and impact.

## Key Findings
- **Encryption:** Critical gap identified; credit card data is currently stored in plain text.
- **Access Control:** Lack of "Least Privilege" and "Separation of Duties" principles.
- **Disaster Recovery:** No formalized plan for data recovery or business continuity.
- **Monitoring:** Intrusion Detection Systems (IDS) are not yet implemented.

## Documentation
You can find the detailed audit documents here:
- [Main Audit Report](./Botium_Toys:_Scope_goals_and_risk_assessment_report.pdf)
- [Controls Assessment Checklist](./Control_Categories.pdf)
- [Compliance Checklist (PCI DSS & GDPR)](./Controls_and_compliance_checklist.pdf)

## Recommendations
1. Implement **AES-256 encryption** for all sensitive data at rest and in transit.
2. Enforce **Multi-Factor Authentication (MFA)** and the Principle of Least Privilege across all departments.
3. Develop and test a formal **Disaster Recovery Plan (DRP)**.
4. Integrate an **IDS/IPS** solution into the network architecture for real-time threat detection.
