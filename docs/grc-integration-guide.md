# EIOC GRC Integration Guide v1.0

**Vendor-Neutral Conceptual Standard for Governance, Risk & Compliance Integration**

**Author:** Narnaiezzsshaa Truong  
**Version:** 1.0  
**Date:** January 31, 2026  
**License:** CC BY 4.0  
**Status:** Open Standard (Conceptual Guide)

---

## 1. Purpose

This guide explains how organizations can integrate the Emotional Indicators of Compromise (EIOC) framework into any Governance, Risk, and Compliance (GRC) platform or internal compliance workflow.

It is:

- Vendor-neutral
- Format-agnostic
- Implementation-flexible
- Aligned with NIST AI RMF, ISO/IEC 42001, ISO 27001, and IEEE 7000

**EIOC provides the human-layer controls that GRC systems currently lack.**

---

## 2. Integration Philosophy

EIOC does not prescribe:

- A specific file format
- A specific schema
- A specific database structure
- A specific GRC vendor

Instead, EIOC defines **conceptual invariants** that any system can implement.

GRC platforms integrate EIOC by:

1. Representing emotional-layer events as structured records
2. Mapping those records to controls and subcategories
3. Using EIOC artifacts as evidence
4. Embedding EIOC workflows into existing SOPs
5. Supporting continuous monitoring of emotional-layer risk

This guide explains how.

---

## 3. What GRC Platforms Need to Track

Every GRC platform—regardless of vendor—supports the same conceptual objects:

- Controls
- Risks
- Evidence
- Incidents
- Exceptions
- Tasks / Workflows
- Policies

**EIOC maps cleanly onto all of these.**

---

## 4. EIOC as GRC Controls

EIOC provides operational controls for:

### 4.1 Human-Layer Detection Controls

| Control | Description |
|---------|-------------|
| Emotional Drift | Detect fog, confusion, disorientation |
| Boundary Distortion | Detect pressure to bypass rules |
| Identity Disruption | Detect deepfakes, voice mimicry |
| Cognitive Fog | Detect induced confusion |
| Affinity Pretexting | Detect unearned familiarity |
| Correlated Compromise | Detect multi-indicator events |

These become **control tests** in GRC systems.

### 4.2 Verification Controls

| Control | Description |
|---------|-------------|
| Out-of-band confirmation | Verify via separate channel |
| Known-good channel switching | Use pre-established contacts |
| Token/passphrase verification | Use pre-shared secrets |
| Second-operator review | Involve additional personnel |

These become **mitigation controls**.

### 4.3 Escalation Controls

| Control | Description |
|---------|-------------|
| Tier 2 escalation | Mandatory verification |
| Tier 3 correlated compromise response | Immediate disengagement |
| Tier 4 operator removal | Escalate to second operator |
| Tier 5 incident response | Full organizational response |

These become **incident response controls**.

---

## 5. EIOC as GRC Evidence

GRC platforms require structured evidence. EIOC provides:

| Evidence Artifact | Purpose |
|-------------------|---------|
| Drift Logs | Longitudinal record of emotional-layer events |
| Incident Triage Forms | Structured incident documentation |
| Verification Protocol records | Proof of OOB verification |
| Operator Posture training logs | Proof of training completion |
| SOP updates | Proof of continuous improvement |
| Post-incident reviews | Proof of organizational learning |

These satisfy:

- NIST AI RMF MEASURE
- NIST AI RMF MANAGE
- ISO/IEC 42001 6.4, 7.4, 8.2
- ISO 27001 Annex A (A.5, A.6, A.8)
- IEEE 7000 human-layer oversight requirements

**EIOC becomes the evidence backbone for human-layer compliance.**

---

## 6. EIOC as GRC Risks

EIOC primitives map directly to risk categories:

| EIOC Primitive | GRC Risk Category |
|----------------|-------------------|
| Emotional Drift | Human-AI Interaction Risk |
| Boundary Distortion | Process Integrity Risk |
| Identity Disruption | Social Engineering / Deepfake Risk |
| Cognitive Fog | Explainability / Comprehension Risk |
| Affinity Pretexting | Manipulation / Trust Exploitation Risk |
| Correlated Compromise | Multi-Vector Human-Layer Risk |

These risks can be added to any risk register.

---

## 7. EIOC in GRC Workflows

### 7.1 Control Testing

GRC systems can test:

- Whether drift events were logged
- Whether verification occurred
- Whether escalation was followed
- Whether SOPs were updated

### 7.2 Incident Management

EIOC events become:

- Tier 2+ incidents
- Correlated compromise alerts
- Operator removal events
- Emotional-layer breach patterns

### 7.3 Continuous Monitoring

GRC dashboards can track:

- Drift frequency
- Verification compliance
- Escalation patterns
- Operator load
- High-risk workflows

### 7.4 Policy Management

EIOC integrates into:

- AI oversight policies
- Human-layer risk policies
- Verification policies
- Escalation policies

---

## 8. Integration Steps (Conceptual)

### Step 1 — Add EIOC as a Control Family

Create a control group called:

> "Emotional-Layer Security Controls (EIOC)"

### Step 2 — Add Each Primitive as a Control

One control per primitive:

- EIOC-01: Emotional Drift Detection
- EIOC-02: Boundary Distortion Detection
- EIOC-03: Identity Disruption Detection
- EIOC-04: Cognitive Fog Detection
- EIOC-05: Affinity Pretexting Detection
- EIOC-06: Correlated Compromise Detection
- EIOC-07: Verification Protocol
- EIOC-08: Escalation Protocol
- EIOC-09: Operator Posture Training

### Step 3 — Add Tier Model as a Severity Matrix

| Severity | EIOC Tier | Description |
|----------|-----------|-------------|
| Low | Tier 1 | Single indicator |
| Medium | Tier 2 | Dual indicator |
| High | Tier 3 | Correlated compromise |
| Critical | Tier 4 | Systemic drift cascade |
| Emergency | Tier 5 | Full emotional breach |

### Step 4 — Add Drift Log & Triage Form as Evidence Types

These become selectable evidence categories in your GRC platform.

### Step 5 — Map Controls to NIST AI RMF

Use the [EIOC-NIST AI RMF Control Mapping](nist-ai-rmf-control-mapping.md).

### Step 6 — Add Verification Protocol as a Required Control Test

Verification becomes a required step for Tier 2+ events.

### Step 7 — Add Escalation Ladder to Incident Response

Tier 3–5 events become incident types with defined response procedures.

### Step 8 — Add Operator Posture Training to Compliance Tasks

Training becomes a recurring compliance requirement (e.g., annual, or upon onboarding).

---

## 9. What This Enables

With EIOC integrated, GRC platforms can:

- Detect emotional-layer anomalies
- Document drift events
- Enforce verification
- Track escalation
- Generate audit evidence
- Trend human-layer risk
- Satisfy NIST AI RMF human-layer requirements
- Support ISO/IEC 42001 certification
- Demonstrate oversight to regulators

**This is the missing operational layer in AI governance.**

---

## 10. Conformance Statement

An organization may claim **EIOC GRC Integration Conformance** if:

1. EIOC primitives are represented as controls.
2. Drift Logs and Triage Forms are accepted as evidence.
3. Tier escalation is embedded in incident workflows.
4. Verification is required for Tier 2+ events.
5. EIOC controls are mapped to NIST AI RMF.

---

## 11. Related Resources

- [EIOC Implementation Starter Kit](implementation-starter-kit.md)
- [EIOC Standards Crosswalk](standards-crosswalk.md)
- [EIOC-NIST AI RMF Control Mapping](nist-ai-rmf-control-mapping.md)
- [EIOC Evidence Model](/specs/eioc-evidence-model.md)

---

## 12. Contact

**Author:** Narnaiezzsshaa Truong  
**Framework:** Emotional Indicators of Compromise (EIOC)  
**Consultancy:** Soft Armor Labs  
**License:** CC BY 4.0

---

**END OF DOCUMENT**
