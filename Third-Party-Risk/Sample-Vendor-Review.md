# Sample Vendor Risk Review

## Vendor Overview
- Vendor Name: CloudMetrics Inc.
- Service Provided: Cloud monitoring and alerting services
- Data Access Level: Limited (metadata only)
- Business Criticality: Medium

**Description of Services:**

CloudMetrics provides a cloud-based monitoring and alerting platform that collects, analyzes,
and visualizes system performance metrics, logs, and operational telemetry from TujaePay’s
cloud infrastructure. The service enables real-time visibility into application health,
system availability, and security-relevant events.

CloudMetrics supports TujaePay by helping engineering and security teams quickly detect
service outages, performance degradation, and anomalous system behavior. This improves
incident response times, supports operational resilience, and helps ensure the reliability
and availability of TujaePay’s SaaS platform without accessing or storing customer PII or
payment data.

**Description of Data Access:**

CloudMetrics is granted read-only access to TujaePay’s cloud monitoring data, including system
performance metrics, application logs, and infrastructure telemetry. This data is limited to
operational and technical metadata and does not include customer PII, payment information,
authentication credentials, or sensitive business records.

Access is restricted to monitoring endpoints and is used solely for the purpose of providing
alerting, visualization, and operational insights. CloudMetrics does not have the ability to
modify systems, configurations, or production data.

---

## Risk Assessment Summary

| Risk Area | Assessment |
|----------|-----------|
| Data Sensitivity | Medium |
| System Access | Read-only |
| Regulatory Impact | Low |
| Business Dependency | Medium |

Overall Vendor Risk Rating: Medium

---

## Security Assessment
- SOC 2 Type II Report Provided: Yes
- Coverage Period: 12 months
- Exceptions Noted: None

### Controls Reviewed
- Logical access controls
- Encryption in transit
- Incident response procedures
- Vendor security governance

---

## Identified Risks and Mitigations

| Risk | Mitigation |
|------|-----------|
| Over-permissioned access | Contractual access restrictions |
| Vendor service disruption | SLA enforcement and monitoring |

---

## Approval and Review
- Reviewed By: GRC Team
- Review Date: January 2026
- Next Review Date: January 2027
- Approval Status: Approved

---

## Notes
Vendor risk assessments are conducted annually and upon significant changes to vendor services.
