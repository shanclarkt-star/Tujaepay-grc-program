# SOC 2 Control Mapping

## 1. What Is SOC 2?
SOC 2 is an auditing standard developed by the AICPA that evaluates how organizations manage
and protect customer data. It is based on the Trust Services Criteria (TSC) and focuses on
security, availability, confidentiality, processing integrity, and privacy.

---

## 2. Purpose of This Mapping
The purpose of this document is to map TujaePay’s security and operational controls to the
SOC 2 Trust Services Criteria in order to:
- Assess SOC 2 readiness
- Demonstrate control coverage
- Identify gaps and remediation needs
- Support internal and external audits

---

## 3. Scope
This mapping applies to:
- TujaePay’s SaaS platform
- Cloud infrastructure (AWS)
- Internal systems supporting operations
- Third-party services impacting security or availability

---

## 4. Mapping Methodology
Each SOC 2 control was evaluated against TujaePay’s implemented controls.
Control status is defined as:

- Implemented: Control is designed and operating effectively
- Partially Implemented: Control exists but requires improvement
- Gap: Control is missing or ineffective

Evidence is reviewed to validate control implementation.

---

## 5. SOC 2 Trust Services Criteria Overview

- CC: Common Criteria (Security)
- A: Availability
- C: Confidentiality
- PI: Processing Integrity
- P: Privacy

---

## 6. SOC 2 Control Mapping Table

| SOC 2 Control | Description | TujaePay Implementation | Evidence | Status |
|--------------|-------------|-------------------------|----------|--------|
| CC1.1 | Control environment | Governance and security oversight established | Risk Management Charter | Implemented |
| CC2.1 | Communication of policies | Security policies documented and communicated | Information Security Policy | Implemented |
| CC3.2 | Risk identification | Risks identified and tracked | Risk Register | Implemented |
| CC4.1 | Monitoring controls | Logging and monitoring implemented | Monitoring procedures | Implemented |
| CC5.2 | Control activities | Access controls enforced | Access Control Policy | Implemented |
| CC6.1 | Logical access | MFA and RBAC enforced | IAM configuration | Implemented |
| CC6.6 | Access reviews | Periodic access reviews performed | Access review records | Partially Implemented |
| CC7.2 | Incident response | Incident response plan established | Incident Response Policy | Implemented |
| CC9.2 | Vendor risk | Vendor risk assessments performed | Vendor reviews | Implemented |
| A1.2 | System availability | Monitoring and alerting in place | CloudMetrics reports | Implemented |

---

## 7. Gap Tracking and Remediation
Controls assessed as Partially Implemented or Gap are documented in the Risk Register and
tracked to remediation through internal audits.

---

## 8. Review and Maintenance
This mapping is reviewed annually and prior to SOC 2 audits or significant system changes.

