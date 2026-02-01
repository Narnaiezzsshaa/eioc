# EIOC Evidence Model v1.0

**Conceptual Specification for Emotional-Layer Compromise Recordkeeping**

**Author:** Narnaiezzsshaa Truong  
**Version:** 1.0  
**Date:** January 31, 2026  
**License:** CC BY 4.0  
**Status:** Open Standard (Conceptual Model)  
**DOI:** 10.5281/zenodo.18446374

---

## 1. Purpose

The EIOC Evidence Model defines the conceptual structure required to document, classify, and audit emotional-layer security events. It is format-agnostic and may be implemented in any technical environment, including:

- GRC platforms
- Ticketing systems
- Incident response tools
- Internal databases
- Spreadsheets
- Custom logging systems

This model ensures that emotional-layer events are:

- Observable
- Documentable
- Auditable
- Mappable to governance frameworks (NIST AI RMF, ISO 27001, etc.)
- Interoperable across platforms

---

## 2. Design Principles

1. **Format Neutrality** — The model defines concepts, not file formats.
2. **Vendor Neutrality** — Any GRC or compliance platform may implement it.
3. **Forward Compatibility** — The model must survive future technologies and schemas.
4. **Minimal Required Fields** — Only essential conceptual elements are mandated.
5. **Extensibility** — Organizations may add fields without breaking compliance.

---

## 3. Core Conceptual Components

Every EIOC event record must contain the following conceptual elements.

### 3.1 Indicator Identity

| Element | Description |
|---------|-------------|
| Indicator ID | Unique identifier for this record |
| Indicator Name | Human-readable name of the primitive |
| Indicator Category | Classification (drift, boundary distortion, etc.) |
| Indicator Definition | Definition of the indicator as triggered |

**Purpose:** Uniquely identify the emotional-layer signal.

---

### 3.2 Detection Context

| Element | Description |
|---------|-------------|
| Timestamp | When the indicator was detected |
| Operator | Who detected the indicator |
| Workflow / System | Where the detection occurred |
| Interaction Channel | Communication medium (phone, email, chat, etc.) |
| Triggering Event | What initiated the detection |

**Purpose:** Establish when, where, and under what conditions the indicator occurred.

---

### 3.3 Observed Symptoms

| Element | Description |
|---------|-------------|
| Symptom Type | Classification of the symptom |
| Symptom Description | Narrative description of what was observed |
| Operator Sensation | What the operator felt (fog, pressure, etc.) |
| Interaction Pattern | Pattern observed (urgency script, affinity pull, etc.) |

**Purpose:** Capture the human-layer manifestation of the event.

---

### 3.4 Tier Classification

| Element | Description |
|---------|-------------|
| Tier Level | Numeric severity (1–5) |
| Number of Indicators Present | Count of co-occurring indicators |
| Correlation Pattern | Classification (single, dual, correlated, systemic, breach) |

**Purpose:** Determine severity and required response.

**Tier Reference:**

| Level | Indicators | Classification | Required Response |
|-------|------------|----------------|-------------------|
| 1 | One | Single Drift Event | Pause + name drift |
| 2 | Two | Dual Indicator Event | Mandatory OOB verification |
| 3 | Three+ | Correlated Compromise | Immediate disengagement |
| 4 | Destabilization | Systemic Drift Cascade | Escalate to second operator |
| 5 | Breach | Full Emotional Breach | Remove operator from loop |

---

### 3.5 Verification Outcome

| Element | Description |
|---------|-------------|
| Verification Performed | Whether verification was attempted (yes/no) |
| Verification Method | Method used (channel switch, callback, token, etc.) |
| Verification Result | Outcome (confirmed legitimate, confirmed suspicious, inconclusive) |

**Purpose:** Document whether the operator validated the interaction.

---

### 3.6 Operator Response

| Element | Description |
|---------|-------------|
| Circuit Breaker Used | Whether a circuit breaker cue was invoked |
| Escalation Triggered | Whether escalation was initiated |
| Operator Removed from Loop | Whether the operator was removed |
| Second Operator Involved | Whether a second operator was brought in |

**Purpose:** Record the human response to the emotional-layer event.

---

### 3.7 Remediation & Recovery

| Element | Description |
|---------|-------------|
| Remediation Action | Action taken to address the incident |
| SOP Reference | Reference to applicable standard operating procedure |
| Policy Reference | Reference to applicable policy |
| Follow-Up Required | Whether follow-up is needed |
| Post-Incident Review Notes | Notes from post-incident review |

**Purpose:** Document organizational response and learning.

---

### 3.8 Compliance Mapping

| Element | Description |
|---------|-------------|
| Mapped Framework(s) | Applicable governance frameworks |
| Mapped Subcategories | Specific subcategories addressed |
| Mapped Requirements | Requirements satisfied |
| Mapped Controls | Control IDs satisfied by this record |

**Purpose:** Connect the emotional-layer event to external governance frameworks.

**Supported Frameworks:**
- NIST AI RMF
- ISO 27001 / ISO 42001
- IEEE 7000 Series
- ACM Code of Ethics
- W3C Anti-Dark-Patterns
- EU AI Act

---

### 3.9 Evidence Artifact

| Element | Description |
|---------|-------------|
| Artifact Type | Type of evidence (log, transcript, form, recording) |
| Artifact Location | URI or path to the artifact |
| Retention Policy | Applicable retention policy |

**Purpose:** Point to the underlying evidence.

---

## 4. Minimal Conformance Requirements

An organization may claim **EIOC Evidence Model Conformance** if:

1. All nine conceptual components are represented in their recordkeeping system.
2. Tier classification follows the EIOC Tier Model (Levels 1–5).
3. Verification outcomes are recorded for Tier 2+ events.
4. Evidence artifacts are retained according to internal policy.
5. Compliance mappings are documented for at least one governance framework (NIST AI RMF recommended).

---

## 5. Implementation Notes (Non-Normative)

- This model may be implemented in any format (YAML, JSON, SQL, CSV, XML, proprietary schemas).
- This model may be integrated into any GRC platform (Hyperproof, AuditBoard, Drata, Tugboat, ServiceNow, etc.).
- This model may be extended with organization-specific fields using a namespace pattern (e.g., `x_org_fieldname`).
- This model does not prescribe storage, encryption, or retention mechanisms — those are organizational decisions.

---

## 6. Versioning & Evolution

This is **EIOC Evidence Model v1.0**.

Future versions will be:
- Publicly released
- Versioned
- DOI'd for citability
- Backward compatible for required fields

Changes to required conceptual components will increment the major version. New optional components may be added without version increment.

---

## 7. Related Resources

- EIOC Implementation Starter Kit (Zenodo DOI pending)
- EIOC Standards Crosswalk (DOI: 10.5281/zenodo.18444566)
- EIOC-NIST AI RMF Integration (DOI: 10.5281/zenodo.18445989)
- GitHub Repository: https://github.com/Narnaiezzsshaa/eioc

---

## 8. Contact

**Author:** Narnaiezzsshaa Truong  
**Framework:** Emotional Indicators of Compromise (EIOC)  
**Consultancy:** Soft Armor Labs  
**License:** CC BY 4.0

---

**END OF SPECIFICATION**

