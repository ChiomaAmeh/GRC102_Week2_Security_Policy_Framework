# Evidence Bundle 1: Security Policy Hierarchy

## 1.1 Documentation Hierarchy Definitions

| Tier Level | Purpose & Focus | Issuing Authority | Mandatory / Discretionary | Level of Detail |
|------------|----------------|------------------|-------------------------|----------------|
| Policy (Tier 1) | Defines executive management intent, high-level rules, and strategic direction. | CEO & Executive Board | Mandatory Enterprise-wide | High-level strategic principles. |
| Standard (Tier 2) | Establishes non-negotiable technical baselines and metrics. | Information Security Manager | Mandatory Technical Baseline | Specific numeric and technical requirements. |
| Procedure (Tier 3) | Provides sequential operational instructions. | IT Operations & Helpdesk Managers | Mandatory Operational Workflow | Detailed step-by-step instructions. |
| Guideline (Tier 4) | Provides best-practice recommendations. | Security Advisory Teams | Recommended | Flexible advisory guidance. |

---

## 1.2 Legacy Statement Classification

| Statement | Classification |
|------------|----------------|
| Employees must use MFA for remote access. | Policy |
| Configure MFA using the Authenticator App. | Procedure |
| Developers should use parameterised queries. | Guideline |
| NexusTech is committed to protecting confidentiality, integrity, and availability. | Policy |
| Corporate laptops must use BitLocker or FileVault. | Standard |
| Avoid public unsecured Wi-Fi. | Guideline |
| Report security breaches immediately to the IT Helpdesk. | Policy |
| Passwords must be a minimum of 14 characters and contain complexity requirements. | Standard |

---

## 1.3 Security Documentation Hierarchy Diagram

```text
[TIER 1: POLICIES]
Enterprise Information Security Policy
Acceptable Use Policy

│
▼

[TIER 2: STANDARDS]
Password Complexity Standard
Full-Disk Encryption Standard

│
▼

[TIER 3: PROCEDURES]
User Access Request Procedure
MFA Configuration Procedure
Incident Reporting Procedure

│
▼

[TIER 4: GUIDELINES]
Secure Coding Guideline
Public Wi-Fi Guideline
```
