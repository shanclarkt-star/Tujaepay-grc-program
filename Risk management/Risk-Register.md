# TujaePay Risk Register

## 1. Purpose
The Risk Register is the central repository for identifying, tracking, and managing risks across
TujaePay. It supports consistent risk management, leadership oversight, and audit readiness.

---

## 2. Risk Scoring Method

Risks are scored using:
- Likelihood: Low / Medium / High
- Impact: Low / Medium / High

Inherent Risk = Risk before controls  
Residual Risk = Risk after controls

Risk ratings:
- Low: Acceptable risk
- Medium: Requires monitoring or planned mitigation
- High: Requires immediate action or escalation

---

## 3. Enterprise Risk Register

| Risk ID | Risk Category | Risk Description | Likelihood | Impact | Inherent Risk | Key Controls | Residual Risk | Risk Owner | Status |
|--------|---------------|------------------|------------|--------|---------------|--------------|---------------|------------|----------|
| R-001 | Security | Unauthorized access to production systems | Medium | High | High | MFA, RBAC, access reviews, logging | Medium | Security | Open |
| R-002 | Third-Party | Vendor data exposure or service compromise | Low | High | Medium | Vendor risk assessments, SOC 2 review | Low | GRC | Open |
| R-003 | Compliance | Failure to meet regulatory or audit requirements | Medium | Medium | Medium | Compliance mappings, audits, policy reviews | Low | GRC | Open |
| R-004 | Operational | Cloud service outage impacting customers | Medium | High | High | Monitoring, incident response, DR planning | Medium | Engineering | Open |
| R-005 | Security | Phishing or credential compromise | High | Medium | High | Security awareness training, MFA, email filtering | Medium | Security | Open |
| R-006 | Incident Response | Ineffective response to security incidents | Medium | High | High | IR policy, tabletop exercises, training | Medium | Security | Open |
| R-007 | Access Management | Excessive or outdated user access | Medium | Medium | Medium | Quarterly access reviews, RBAC | Low | IT | Open |
| R-008 | Vendor Dependency | Over-reliance on a critical vendor | Low | Medium | Low | SLA, vendor monitoring, exit strategy | Low | Engineering | Open |

---

## 4. Risk Review and Governance

- The Risk Register is reviewed at least quarterly.
- High risks are reviewed with executive management.
- Risks are updated when:
  - New systems or vendors are introduced
  - Significant incidents occur
  - Control effectiveness changes

---

## 5. Risk Treatment Tracking

For risks requiring mitigation:
- A remediation plan is defined
- An owner is assigned
- Progress is tracked until closure

---

## 6. Status Definitions

- Open: Risk exists and is being managed
- Mitigating: Controls are being implemented
- Accepted: Risk formally accepted by management
- Closed: Risk no longer applicable or fully mitigated
