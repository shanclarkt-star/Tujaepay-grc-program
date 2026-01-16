# NIST Cybersecurity Framework (CSF) Mapping

## 1. What Is the NIST CSF?
The NIST Cybersecurity Framework (CSF) is a risk-based framework developed to help organizations
identify, protect, detect, respond to, and recover from cybersecurity threats.
It is widely used to assess cybersecurity maturity and manage security risk.

---

## 2. Purpose of This Mapping
The purpose of this document is to map TujaePay’s security controls to the NIST CSF in order to:
- Assess cybersecurity risk management maturity
- Identify control gaps and improvement areas
- Demonstrate alignment with industry best practices
- Support internal audits and external assessments

---

## 3. Scope
This mapping applies to:
- Cloud infrastructure (AWS)
- Production and internal systems
- Customer and employee data
- Third-party services supporting TujaePay operations

---

## 4. Mapping Methodology
Each NIST CSF category and subcategory was reviewed against TujaePay’s implemented controls.
Controls are evaluated using the following status definitions:

- **Implemented:** Control is fully implemented and operating effectively
- **Partially Implemented:** Control exists but requires improvement
- **Gap:** Control is missing or ineffective

Evidence is reviewed to validate control design and effectiveness.

---

## 5. NIST CSF Core Functions Overview
The NIST CSF consists of five core functions:
- **Identify (ID):** Understand organizational risk
- **Protect (PR):** Safeguard critical services
- **Detect (DE):** Identify cybersecurity events
- **Respond (RS):** Contain and mitigate incidents
- **Recover (RC):** Restore services and improve resilience

---

## 6. Control Evidence Criteria
Evidence used to support control implementation may include:
- Policies and procedures
- System configurations and screenshots
- Access reviews and audit logs
- Incident response documentation
- Vendor risk assessments

Evidence must be current, relevant, and auditable.

---

## 7. NIST CSF Control Mapping Table

| Function | Category | Subcategory | TujaePay Implementation | Evidence | Status |
|---------|----------|-------------|-------------------------|----------|--------|
| ID | Asset Management | ID.AM-1 | Asset inventory maintained | Asset register | Implemented |
| ID | Risk Assessment | ID.RA-1 | Annual risk assessments performed | Risk register | Implemented |
| PR | Access Control | PR.AC-1 | IAM roles and MFA enforced | Access Control Policy | Implemented |
| PR | Data Security | PR.DS-1 | Encryption in transit | Security standards | Implemented |
| DE | Anomalies | DE.AE-2 | Centralized logging | Monitoring tools | Implemented |
| RS | Response Planning | RS.RP-1 | Incident response plan defined | IR Policy | Implemented |
| RC | Recovery Planning | RC.RP-1 | Backup and recovery procedures | DR documentation | Partially Implemented |

---

## 8. Gap Management and Risk Tracking
Controls assessed as **Partially Implemented** or **Gap** are documented in the TujaePay risk register,
assigned an owner, and tracked through remediation.

---

## 9. Review and Maintenance
This mapping is reviewed annually or following significant changes to TujaePay’s systems,
threat landscape, or regulatory requirements.
