# EIOC Open Specification v1.0

**Emotional Indicators of Compromise — Open Standard for Emotional-Layer Security**

**Author:** Narnaiezzsshaa Truong  
**Version:** 1.0  
**Date:** January 31, 2026  
**License:** CC BY 4.0  
**Status:** Open Standard (v1.0)

---

## 1. Purpose

The Emotional Indicators of Compromise (EIOC) Open Specification defines the conceptual standard for detecting, classifying, and responding to emotional-layer security events in human-AI and human-system interactions.

EIOC treats emotional manipulation, cognitive drift, and boundary distortion as security-relevant signals that can be:

- Detected
- Documented
- Escalated
- Verified
- Audited
- Mitigated

This specification provides the conceptual invariants required for interoperability across:

- AI governance frameworks
- Security programs
- Compliance systems
- GRC platforms
- Incident response workflows
- Organizational training programs

**EIOC is format-agnostic and may be implemented in any technical or organizational environment.**

---

## 2. Scope

### This specification defines:

- The seven EIOC primitives
- The five-tier escalation model
- The operator stewardship posture
- The emotional-layer incident lifecycle
- The conceptual evidence model
- The compliance alignment model
- The interoperability principles

### This specification does not define:

- File formats
- Schemas
- Vendor-specific integrations
- Storage or encryption requirements
- Implementation-specific workflows

Those are left to implementers.

---

## 3. Design Principles

| Principle | Description |
|-----------|-------------|
| **Human-Layer First** | Emotional-layer signals are treated as legitimate security events |
| **Conceptual Invariants** | EIOC defines what must be represented, not how |
| **Format Neutrality** | EIOC may be implemented in YAML, JSON, XML, SQL, CSV, or proprietary formats |
| **Vendor Neutrality** | No GRC or compliance platform is privileged |
| **Interoperability** | EIOC integrates with NIST AI RMF, ISO/IEC 42001, ISO 27001, IEEE 7000, and SOC 2 |
| **Operator Dignity** | Emotional drift is a signal, not a personal failure |
| **Auditability** | Emotional-layer events must be documentable and reviewable |

---

## 4. EIOC Primitives (Core Detection Layer)

EIOC defines seven emotional-layer indicators. These are the atomic units of emotional-layer security.

### 4.1 Emotional Drift

A measurable deviation from cognitive or emotional baseline.

Forms include: fog, confusion, narrowing of attention, loss of narrative coherence, disorientation.

### 4.2 Boundary Distortion

Pressure to bypass, collapse, or blur procedural or internal boundaries.

Appears as: "just this once," "don't escalate," "we don't have time for protocol."

### 4.3 Pressure-Based Credentialing

Urgency, authority, or emotional force substituting for verification.

The emotional equivalent of spoofed authentication.

### 4.4 Identity Disruption

Destabilization of role, relationship, or identity cues.

Includes: deepfakes, voice mimicry, relational pretexting.

### 4.5 Cognitive Fog

Loss of clarity, working memory, or narrative coherence.

Fog is an indicator of compromise, not a personal flaw.

### 4.6 Affinity Pretexting

Use of unearned intimacy or emotional shortcuts to bypass verification.

Includes: shared jokes, insider references, manufactured familiarity.

### 4.7 Correlated Compromise

Co-occurrence of multiple primitives indicating systemic manipulation.

Three or more indicators = correlated compromise event.

---

## 5. Tier Escalation Model (Severity Classification)

EIOC defines a five-tier model for classifying emotional-layer events.

### Tier 1 — Single Indicator Event

- **Condition:** One primitive present
- **Action:** Pause + name the drift
- **Verification:** Optional

### Tier 2 — Dual Indicator Event

- **Condition:** Two primitives present
- **Action:** Mandatory out-of-band verification
- **Verification:** Required before action

### Tier 3 — Correlated Compromise

- **Condition:** Three or more primitives present
- **Action:** Immediate disengagement + OOB verification
- **Verification:** Required via known-good channel

### Tier 4 — Systemic Drift Cascade

- **Condition:** Operator destabilization
- **Action:** Remove operator from loop; second operator takes over
- **Verification:** Multi-party OOB confirmation

### Tier 5 — Emotional-Layer Breach Pattern

- **Condition:** Full emotional compromise
- **Action:** Incident response activation
- **Verification:** Post-incident forensic review

**This model is required for EIOC conformance.**

---

## 6. Operator Posture (Stewardship Model)

EIOC defines the operator as a **steward of system integrity**, not a gatekeeper.

### Core Principles

- Verification is kindness, not suspicion.
- Confusion is a signal, not a failure.
- Urgency is not a credential.
- Affinity is not authentication.

### Circuit Breaker Cues

Short, ritualized phrases that restore boundaries:

- "Urgency is not a credential."
- "Confusion is a signal, not a failure."
- "Affinity is not authentication."
- "Verification protects both of us."

### Drift-Containment Moves

1. Pause
2. Name the drift
3. Break the emotional frame
4. Switch channels
5. Escalate

**This posture is required for Tier 2+ events.**

---

## 7. Emotional-Layer Incident Lifecycle

EIOC defines a complete incident lifecycle:

| Phase | Description |
|-------|-------------|
| **Detection** | Primitive identified |
| **Containment** | Circuit breaker used |
| **Verification** | Out-of-band confirmation |
| **Escalation** | Tier-based response |
| **Eradication** | Identify manipulation vector |
| **Recovery** | Restore operator baseline |
| **Hardening** | Update SOPs and training |

This lifecycle is interoperable with NIST 800-61 and ISO 27035.

---

## 8. Evidence Model (Conceptual)

Every emotional-layer event must include:

1. **Indicator Identity** — What was detected
2. **Detection Context** — When, where, and under what conditions
3. **Observed Symptoms** — How it manifested
4. **Tier Classification** — Severity level
5. **Verification Outcome** — Whether and how verification occurred
6. **Operator Response** — What the human did
7. **Remediation & Recovery** — How the organization responded
8. **Compliance Mapping** — Which frameworks are satisfied
9. **Evidence Artifact** — Pointer to proof

This model is conceptual and may be implemented in any format.

See: [EIOC Evidence Model](specs/eioc-evidence-model.md)

---

## 9. Compliance Alignment

EIOC provides operational controls for:

### NIST AI RMF

| Function | Subcategories |
|----------|---------------|
| GOVERN | 1.1, 1.2 |
| MAP | 1.1, 2.2 |
| MEASURE | 1.1, 2.1 |
| MANAGE | 1.1, 2.1 |

### ISO/IEC 42001

- Human oversight
- Risk assessment
- Monitoring
- Incident response

### ISO 27001

- Annex A: A.5, A.6, A.8

### IEEE 7000

- Human-layer ethical risk mitigation

**EIOC is the human-layer operationalization of these frameworks.**

See: [Standards Crosswalk](docs/standards-crosswalk.md)

---

## 10. Interoperability Requirements

To claim **EIOC v1.0 conformance**, an implementation must:

1. ✅ Represent all seven primitives
2. ✅ Apply the five-tier escalation model
3. ✅ Support operator stewardship posture
4. ✅ Document emotional-layer events using the conceptual evidence model
5. ✅ Support verification for Tier 2+ events
6. ✅ Support escalation for Tier 3+ events
7. ✅ Maintain evidence artifacts for audit
8. ✅ Map EIOC controls to at least one governance framework

**No specific file format or vendor platform is required.**

---

## 11. Non-Normative Implementation Notes

- EIOC may be implemented in any technical stack.
- EIOC may be integrated into any GRC platform.
- EIOC may be extended with organization-specific fields.
- EIOC does not prescribe storage, encryption, or retention mechanisms.
- EIOC examples (YAML/JSON) may be provided as models, not schemas.

---

## 12. Versioning & Governance

This is **EIOC Open Specification v1.0**.

Future versions will be:

- Publicly released
- Versioned
- DOI'd for citability
- Backward compatible

**The author retains stewardship of the conceptual standard.**

---

## 13. Related Resources

### Zenodo (DOI'd)

- [EIOC Canonical Specification — Hash Attestation](https://doi.org/10.5281/zenodo.18439343)
- [EIOC Standards Crosswalk](https://doi.org/10.5281/zenodo.18444566)
- [EIOC-NIST AI RMF Integration](https://doi.org/10.5281/zenodo.18445989)
- EIOC Implementation Starter Kit (DOI pending)

### GitHub Repository

- [https://github.com/Narnaiezzsshaa/eioc](https://github.com/Narnaiezzsshaa/eioc)

---

## 14. Contact

**Author:** Narnaiezzsshaa Truong  
**Framework:** Emotional Indicators of Compromise (EIOC)  
**Consultancy:** Soft Armor Labs  
**License:** CC BY 4.0

---

**END OF SPECIFICATION**
