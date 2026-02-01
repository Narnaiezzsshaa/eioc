# Security Policy

**EIOC Open Standard — Vulnerability Disclosure**

---

## 1. Purpose

This document defines how emotional-layer vulnerabilities, conceptual defects, and implementation risks related to the EIOC Open Standard should be reported and handled.

Because EIOC is a conceptual, format-agnostic standard, security issues relate to:

- Misinterpretations of the standard
- Incorrect tier logic
- Misuse of primitives
- Unsafe or misleading implementations
- Documentation gaps that could cause operator harm
- Integrations that distort the intent of the framework

This policy ensures that the standard remains safe, interoperable, and aligned with its stewardship posture.

---

## 2. What Constitutes a Security Issue

EIOC does not contain executable code. Security issues therefore refer to **conceptual or operational risks**, including:

### 2.1 Misclassification Risks

- Incorrect tier thresholds
- Primitives collapsed or merged in unsafe ways
- Escalation logic altered in ways that reduce operator safety

### 2.2 Misuse in High-Risk Environments

- Implementations that pressure operators to ignore drift
- Removal of verification steps
- Coercive or punitive use of emotional-layer indicators

### 2.3 Harmful Interpretations

- Interpretations that shame operators
- Interpretations that treat emotional drift as a personal flaw
- Interpretations that violate the stewardship posture

### 2.4 Compliance Misalignment

- Incorrect mappings to NIST AI RMF
- Evidence models that omit required conceptual elements
- Integrations that misrepresent EIOC as a product or tool

### 2.5 Documentation Vulnerabilities

- Ambiguous definitions
- Unclear escalation guidance
- Missing safety notes for implementers

**If you are unsure whether something qualifies, report it anyway.**

---

## 3. How to Report a Security Issue

Please submit a private disclosure via email:

📧 **[security contact to be added]**

Include:

- Description of the issue
- Location in the repository (file, section, line if applicable)
- Potential impact
- Suggested remediation (optional)

**Do not open a public GitHub issue for security-relevant concerns.**

---

## 4. Response Process

| Step | Timeline |
|------|----------|
| Acknowledgment | Within 72 hours |
| Initial assessment | Within 7 days |
| Remediation plan drafted | Within 14 days |
| Public disclosure (if applicable) | After remediation |

All disclosures will credit the reporter unless anonymity is requested.

---

## 5. Scope

### In Scope

This policy applies to:

- The EIOC Open Specification
- The EIOC–NIST AI RMF mapping
- The Evidence Model
- The GRC Integration Guide
- Case studies
- Reference models (YAML/JSON examples)

### Out of Scope

This policy does not apply to:

- Third-party implementations
- Vendor-specific schemas
- Proprietary forks

---

## 6. Stewardship Commitment

EIOC is an open standard. Its safety depends on:

- Clarity
- Interpretive integrity
- Operator dignity
- Correct implementation

We welcome responsible disclosures that strengthen the framework and protect operators.

---

**Author:** Narnaiezzsshaa Truong  
**Framework:** Emotional Indicators of Compromise (EIOC)  
**License:** CC BY 4.0
