# EIOC — Emotional Indicators of Compromise

**An Open Standard for Human-Layer Security**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18445989.svg)](https://doi.org/10.5281/zenodo.18445989)

---

## Overview

This repository provides the **EIOC Open Standard** — a complete, implementable, and vendor-neutral framework for detecting, classifying, and responding to emotional-layer security events in human-AI and human-system interactions.

EIOC operationalizes the human-layer requirements of governance frameworks by providing:

- Emotional-layer detection primitives
- Tiered escalation logic
- Operator stewardship posture
- Verification rituals
- Incident response workflows
- Audit-ready evidence models

EIOC integrates with:

- **NIST AI Risk Management Framework (AI RMF) 1.0**
- **ISO/IEC 42001** (AI Management)
- **ISO 27001** (Information Security)
- **IEEE 7000** (Ethical AI)
- **SOC 2**

---

## Purpose

This repository provides:

- A conceptual control mapping between EIOC and governance frameworks
- A format-agnostic evidence model for emotional-layer events
- Implementation guidance for compliance officers and auditors
- Operational templates for frontline teams
- Case studies demonstrating real-world adoption
- Reference models (non-normative) for structured representations

**This repository does not prescribe any specific file format, schema, or vendor platform.**

---

## Repository Structure

```
eioc/
├── SPECIFICATION.md                     # EIOC Open Specification v1.0 (master document)
├── README.md                            # This file
├── LICENSE
│
├── docs/
│   ├── implementation-starter-kit.md    # Full framework + tools
│   ├── standards-crosswalk.md           # ISO/IEEE/W3C/ACM mapping
│   ├── nist-ai-rmf-mapping.md           # NIST AI RMF integration (overview)
│   ├── nist-ai-rmf-control-mapping.md   # NIST AI RMF control crosswalk (detailed)
│   ├── grc-integration-guide.md         # GRC platform integration guide
│   └── case-studies/
│       └── saas-support-team.md         # Pilot case study
│
├── templates/
│   ├── detection-card.md                # One-page quick reference
│   ├── incident-triage-form.md          # Structured incident documentation
│   ├── drift-log.md                     # Longitudinal event tracking
│   └── verification-protocol.md         # OOB verification ritual
│
├── training/
│   └── operator-posture-module.md       # 45-minute training module
│
└── specs/
    ├── eioc-evidence-model.md           # Conceptual data model for recordkeeping
    └── examples/
        ├── indicator-record-example.yaml
        └── indicator-record-example.json
```

---

## Core Documents

### 1. EIOC Open Specification v1.0

Defines the conceptual standard for emotional-layer security.

- Format-agnostic
- Vendor-neutral
- The canonical source for EIOC primitives, tiers, posture, and lifecycle

**[Read the Specification →](SPECIFICATION.md)**

### 2. EIOC–NIST AI RMF Control Mapping

Shows how EIOC satisfies human-layer requirements across:

| Function | Coverage |
|----------|----------|
| **GOVERN** | Organizational culture, human roles |
| **MAP** | Contextual risk identification |
| **MEASURE** | Trustworthiness assessment, anomaly monitoring |
| **MANAGE** | Risk mitigation, incident response |

This is the primary reference for auditors and compliance teams.

**[Read the Control Mapping →](docs/nist-ai-rmf-control-mapping.md)**

### 3. EIOC Evidence Model

Defines the conceptual structure required to document emotional-layer events.

- Not a schema
- Not tied to any format
- Implementable in any GRC platform

**[Read the Evidence Model →](specs/eioc-evidence-model.md)**

### 4. EIOC GRC Integration Guide

Vendor-neutral guidance for integrating EIOC into:

- AuditBoard
- Hyperproof
- Drata
- Tugboat
- Vanta
- ServiceNow
- Internal compliance systems

**[Read the Integration Guide →](docs/grc-integration-guide.md)**

---

## The Seven Primitives

| Primitive | What it detects |
|-----------|-----------------|
| **Emotional Drift** | Fog, confusion, disorientation under pressure |
| **Boundary Distortion** | Pressure to bypass rules ("just this once") |
| **Pressure-Based Credentialing** | Urgency or authority used as fake authentication |
| **Identity Disruption** | Deepfakes, voice mimicry, relational pretexting |
| **Cognitive Fog** | Induced confusion, loss of logical thread |
| **Affinity Pretexting** | Unearned familiarity used to bypass verification |
| **Correlated Compromise** | Multiple indicators = systemic attack |

---

## Tier Escalation Model

| Level | Indicators | Response |
|-------|------------|----------|
| 1 | One | Pause + name the drift |
| 2 | Two | Mandatory OOB verification |
| 3 | Three+ | Immediate disengagement |
| 4 | Operator destabilization | Escalate to second operator |
| 5 | Full breach pattern | Remove operator from loop |

---

## Quick Start

1. **Read** the [EIOC Open Specification](SPECIFICATION.md) for the authoritative standard
2. **Deploy** the [Detection Card](templates/detection-card.md) to your team
3. **Train** operators using the [Posture Module](training/operator-posture-module.md)
4. **Log** drift events with the [Drift Log](templates/drift-log.md)
5. **Triage** incidents with the [Triage Form](templates/incident-triage-form.md)
6. **Integrate** with your GRC platform using the [Integration Guide](docs/grc-integration-guide.md)

---

## Conformance

An organization may claim **EIOC v1.0 Conformance** if:

1. ✅ EIOC primitives are used to detect emotional-layer risks
2. ✅ Tier escalation is applied to multi-indicator events
3. ✅ Verification is required for Tier 2+ events
4. ✅ Drift Logs and Triage Forms are maintained as evidence
5. ✅ EIOC controls are mapped to at least one governance framework

---

## Models (Non-Normative)

The `/specs/examples/` directory contains example representations of EIOC indicators in structured formats (YAML, JSON).

These are:

- Illustrative
- Optional
- Non-canonical
- Provided for implementers

**The EIOC standard remains format-agnostic.**

---

## Related Publications

| Document | DOI |
|----------|-----|
| EIOC Canonical Specification — Hash Attestation | [10.5281/zenodo.18439343](https://doi.org/10.5281/zenodo.18439343) |
| EIOC Standards Crosswalk — ISO, IEEE, W3C, ACM | [10.5281/zenodo.18444566](https://doi.org/10.5281/zenodo.18444566) |
| EIOC–NIST AI RMF Integration | [10.5281/zenodo.18445989](https://doi.org/10.5281/zenodo.18445989) |
| EIOC Implementation Starter Kit | DOI pending |

---

## License

All materials in this repository are released under:

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

This ensures:

- Open access
- Free reuse
- Citation integrity
- Standards-grade transparency

---

## Citation

```bibtex
@misc{truong2026eioc,
  author = {Truong, Narnaiezzsshaa},
  title = {EIOC: Emotional Indicators of Compromise},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/Narnaiezzsshaa/eioc},
  doi = {10.5281/zenodo.18445989}
}
```

---

## Author

**Narnaiezzsshaa Truong**  
Framework: Emotional Indicators of Compromise (EIOC)  
Consultancy: Soft Armor Labs  
License: CC BY 4.0

---

> *"Standards tell us what must not be violated. EIOC tells us how to feel the violation as it begins."*
