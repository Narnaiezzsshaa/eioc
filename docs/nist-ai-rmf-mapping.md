# EIOC-NIST AI RMF Integration: Mapping Emotional-Layer Governance to the AI Risk Management Framework

**Author:** Narnaiezzsshaa Truong  
**Version:** 1.0  
**Date:** January 31, 2026  
**License:** CC BY 4.0

---

## Abstract

The NIST AI Risk Management Framework (AI RMF) establishes a comprehensive governance structure for responsible AI deployment through four core functions: Govern, Map, Measure, and Manage. While the AI RMF acknowledges human-layer risks—including manipulation, autonomy erosion, and emotional harm—it does not specify mechanisms for detecting or mitigating these risks at the emotional layer. The Emotional Indicators of Compromise (EIOC) framework provides the missing instrumentation: a structured set of emotional-layer detection primitives, operator posture protocols, and a tiered escalation model that operationalize the human-layer commitments embedded in the AI RMF. This document maps EIOC primitives and tools to each RMF function, demonstrating how EIOC completes the AI governance stack.

---

## Introduction

The NIST AI Risk Management Framework (AI RMF) outlines four core functions for responsible AI governance:

- **Govern:** Establish organizational policies, roles, and accountability
- **Map:** Understand system context, capabilities, and risks
- **Measure:** Evaluate system performance, risks, and impacts
- **Manage:** Implement controls, monitor, and respond to risks

While the AI RMF acknowledges human-layer risks—including manipulation, autonomy erosion, and emotional harm—it does not specify mechanisms for detecting or mitigating these risks.

EIOC provides the missing instrumentation. It introduces emotional-layer detection primitives, operator posture protocols, and a tiered escalation model that operationalize the human-layer commitments embedded in the AI RMF.

---

## Function 1: GOVERN

**RMF Goal:** Establish policies, roles, and accountability structures for AI risk management.

### EIOC Alignment

**Organizational policies on human-layer risk:**  
*RMF element:* Policies must address human factors and manipulation risks.  
*EIOC contribution:* EIOC defines emotional compromise as a measurable risk class with formal detection primitives.

**Role definitions:**  
*RMF element:* Clear roles for AI risk oversight.  
*EIOC contribution:* EIOC introduces the "Operator as Steward" posture—a defined role identity with emotional-layer responsibilities.

**Accountability structures:**  
*RMF element:* Mechanisms for escalation and documentation.  
*EIOC contribution:* EIOC tier model enables structured escalation and documentation of emotional compromise events.

**Training and awareness:**  
*RMF element:* Personnel must understand AI risks and their roles.  
*EIOC contribution:* EIOC Operator Posture Training module provides emotional-layer SOC onboarding with circuit breaker cues and verification rituals.

### Interpretation

EIOC enables organizations to govern emotional-layer risk with the same rigor as technical risk, embedding stewardship posture and tiered response into policy.

---

## Function 2: MAP

**RMF Goal:** Understand the AI system's context, capabilities, and risk surface.

### EIOC Alignment

**System context and user interaction:**  
*RMF element:* Map how users interact with AI systems.  
*EIOC contribution:* EIOC maps emotional manipulation vectors (urgency, affinity, identity mimicry) as attack surfaces.

**Risk identification:**  
*RMF element:* Identify potential harms and vulnerabilities.  
*EIOC contribution:* EIOC primitives (drift, boundary distortion, cognitive fog, identity disruption, affinity pretexting, pressure-based credentialing) define emotional compromise indicators.

**Stakeholder roles:**  
*RMF element:* Clarify responsibilities across stakeholders.  
*EIOC contribution:* EIOC clarifies operator responsibilities and verification rituals with the Verification Protocol Sheet.

**Environmental factors:**  
*RMF element:* Account for contextual variables affecting risk.  
*EIOC contribution:* EIOC Drift Log captures longitudinal emotional-layer anomalies, enabling pattern recognition across contexts.

### Interpretation

EIOC expands the system map to include emotional-layer attack surfaces and operator-level compromise patterns.

---

## Function 3: MEASURE

**RMF Goal:** Evaluate system performance, risks, and impacts.

### EIOC Alignment

**Risk metrics:**  
*RMF element:* Quantifiable measures of AI risk.  
*EIOC contribution:* EIOC tier model (Levels 1-5) provides structured escalation thresholds based on indicator count and severity.

**Performance indicators:**  
*RMF element:* Track system behavior and outcomes.  
*EIOC contribution:* EIOC Drift Log and Incident Triage Form generate measurable emotional-layer data for trend analysis.

**Auditability:**  
*RMF element:* Documentation for compliance review.  
*EIOC contribution:* EIOC Verification Protocol and Triage Form create audit-ready compliance artifacts.

**Impact assessment:**  
*RMF element:* Evaluate consequences of AI system behavior.  
*EIOC contribution:* EIOC enables detection of emotional harm and manipulation before technical compromise occurs—leading indicator, not lagging.

### Interpretation

EIOC provides the metrics, forms, and escalation logic needed to measure emotional-layer risk with audit-grade fidelity.

---

## Function 4: MANAGE

**RMF Goal:** Implement controls, monitor risks, and respond to incidents.

### EIOC Alignment

**Controls implementation:**  
*RMF element:* Deploy mechanisms to mitigate identified risks.  
*EIOC contribution:* EIOC Detection Card and Verification Protocol Sheet operationalize emotional-layer controls for frontline operators.

**Monitoring:**  
*RMF element:* Continuous observation of system behavior and risks.  
*EIOC contribution:* EIOC Drift Log enables continuous operator-level monitoring with structured entry templates.

**Incident response:**  
*RMF element:* Structured response to risk events.  
*EIOC contribution:* EIOC Incident Triage Form structures emotional compromise response with indicator checklists, tier classification, and escalation documentation.

**Continuous improvement:**  
*RMF element:* Learn from incidents and harden systems.  
*EIOC contribution:* EIOC tier interpretation sessions support pattern recognition and protocol hardening based on longitudinal drift data.

### Interpretation

EIOC enables organizations to manage emotional-layer risk with repeatable controls, real-time detection, and structured response protocols.

---

## Conclusion

The NIST AI RMF identifies human-layer risk as a critical governance concern but does not specify how to detect or mitigate emotional compromise. EIOC fills this gap by providing:

- Detection primitives (drift, boundary distortion, cognitive fog, identity disruption, affinity pretexting, pressure-based credentialing)
- Operator posture protocols (Stewardship stance, circuit breaker cues)
- Tiered escalation logic (Levels 1-5 based on correlated indicator count)
- Audit-ready artifacts (Incident Triage Form, Verification Protocol Sheet)
- Training modules (Operator Posture Training)
- Longitudinal monitoring tools (Drift Log)

EIOC does not extend the AI RMF. It completes it.

---

## Related Identifiers

- EIOC Canonical Specification v0.9 — Hash Attestation (DOI: 10.5281/zenodo.18439343)
- EIOC Standards Crosswalk v1.0 — ISO, IEEE, W3C, ACM (DOI: 10.5281/zenodo.18444566)

---

**END OF DOCUMENT**
