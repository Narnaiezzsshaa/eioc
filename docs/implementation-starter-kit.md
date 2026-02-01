# EIOC Implementation Starter Kit

**A Complete Framework for Emotional-Layer Security**

**Author:** Narnaiezzsshaa Truong  
**Version:** 1.0  
**Date:** January 31, 2026  
**License:** CC BY 4.0

---

## Versioning

This is EIOC v1.0. Future versions will be publicly released and versioned. All versions will be deposited with DOIs to ensure citability and lineage tracking. The canonical source for EIOC is maintained by the author.

---

## Scope & Intent

EIOC (Emotional Indicators of Compromise) is an open standard for human-layer security. It is designed to detect, measure, and respond to emotional manipulation, cognitive compromise, and boundary distortion in operational contexts. EIOC complements existing governance frameworks—including ISO 27001, NIST AI RMF, IEEE 7000, and ACM Code of Ethics—by providing the detection primitives and operator protocols they require but do not specify. EIOC is not a psychological, clinical, or diagnostic tool; it is a security framework for protecting operators and systems from emotional-layer attacks.

---

## Overview

This starter kit provides everything needed to implement the Emotional Indicators of Compromise (EIOC) framework. It includes detection primitives, tier escalation logic, operator protocols, documentation templates, and training guidance.

EIOC operationalizes human-layer security controls required by ISO 27001, NIST AI RMF, IEEE 7000, and other governance frameworks. It treats emotional manipulation as a measurable security event, not a personal failure.

For training, certification, and organizational integration support, contact the author.

---

## Part 1: EIOC Primitives

### The Seven Primitives

| Primitive | Definition |
|-----------|------------|
| **Emotional Drift** | A measurable deviation in cognitive, emotional, or perceptual baseline. Forms include fog, confusion, narrowing of attention, disorientation. |
| **Boundary Distortion** | Any attempt to collapse, bypass, or blur internal or procedural boundaries. Appears as "just this once," "don't escalate," "we don't have time for protocol." |
| **Pressure-Based Credentialing** | When urgency, authority, or emotional force substitutes for verification. The emotional equivalent of spoofed authentication. |
| **Identity Disruption** | Manipulation that destabilizes the operator's sense of who is speaking, what role they are in, what the relationship is. Includes deepfakes and emotional mimicry. |
| **Cognitive Fog** | Sudden inability to track logic, maintain working memory, or follow conversational thread. Fog is an indicator, not a flaw. |
| **Affinity Pretexting** | Use of unearned intimacy, shared jokes, insider references, or emotional shortcuts to bypass verification. |
| **Correlated Compromise** | When multiple primitives co-occur, risk is multiplicative, not additive. Three indicators = systemic compromise event. |

---

## Part 2: Tier Escalation Structure

### Level 1 — Single Drift Event

**Definition:** One emotional indicator appears in isolation.

**Operator Symptoms:**
- Mild confusion
- Slight urgency
- Subtle boundary pressure

**Circuit Breaker:** Pause + name the drift.

**Verification:** Optional.

---

### Level 2 — Dual Indicator Event

**Definition:** Two indicators co-occur.

**Operator Symptoms:**
- Confusion + urgency
- Affinity + fog
- Boundary distortion + pressure

**Circuit Breaker:** Mandatory pause + out-of-band check.

**Verification:** Required before action.

---

### Level 3 — Correlated Compromise Event

**Definition:** Three or more indicators co-occur. This is a compromise, not a suspicion.

**Operator Symptoms:**
- Fog + urgency + affinity
- Identity disruption + pressure + boundary collapse

**Circuit Breaker:** Immediate disengagement using a Stewardship Cue.

**Verification:** Out-of-band confirmation using a known-good channel.

---

### Level 4 — Systemic Drift Cascade

**Definition:** The operator's emotional state is being actively shaped by an adversarial system.

**Operator Symptoms:**
- Inability to self-regulate
- Narrative collapse
- Emotional flooding

**Circuit Breaker:** Escalate to a second operator. Remove the compromised operator from the loop.

**Verification:** Multi-party OOB confirmation.

---

### Level 5 — Full Emotional Breach Pattern

**Definition:** The adversary has achieved emotional-layer root access.

**Operator Symptoms:**
- Compliance without comprehension
- Dissociation
- Total boundary collapse

**Circuit Breaker:** Immediate shutdown of operator access. Invoke organizational incident response.

**Verification:** Post-incident forensic review.

---

## Part 3: Operator Posture — Stewardship

### Core Principles

The operator is not a gatekeeper. They are a steward of system integrity.

- Verification is not suspicion. It is kindness to the system.
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
5. Escalate to a second operator

---

## Part 4: Detection Card (One-Page Reference)

### Primitives Quick Reference

| Primitive | Operator Sensation | Attacker Behavior |
|-----------|-------------------|-------------------|
| Emotional Drift | Fog, disorientation, "I can't think straight" | Overloading, rapid context shifts |
| Boundary Distortion | Pressure to skip steps, bypass rules | "Just this once," "Don't escalate" |
| Pressure-Based Credentialing | Urgency, fear of delay | Countdown, authority pressure |
| Identity Disruption | "This doesn't feel like them" | Deepfake, voice mimicry, insider references |
| Cognitive Fog | Loss of thread, confusion | Legal jargon, speed, complexity |
| Affinity Pretexting | Unearned familiarity | Shared jokes, emotional shortcuts |
| Correlated Compromise | Multiple sensations at once | Multi-vector manipulation |

### Tier Thresholds

- **Level 1:** One indicator → Pause + name the drift
- **Level 2:** Two indicators → Mandatory OOB verification
- **Level 3:** Three indicators → Immediate disengagement
- **Level 4:** Operator destabilization → Escalate to second operator
- **Level 5:** Full emotional breach → Remove operator from loop

### Circuit Breaker Cues

- "Urgency is not a credential."
- "Confusion is a signal, not a failure."
- "Affinity is not authentication."
- "Verification protects both of us."

---

## Part 5: Incident Triage Form

### Incident Summary

- **Date / Time:**
- **Operator:**
- **Channel:** (email, call, chat, in-person)
- **Context:**

### Indicators Observed

Check all that apply:

- [ ] Emotional Drift
- [ ] Boundary Distortion
- [ ] Pressure-Based Credentialing
- [ ] Identity Disruption
- [ ] Cognitive Fog
- [ ] Affinity Pretexting

**Total Indicators:** ___

**Tier Classification:** Level ___

### Actions Taken

- **Circuit Breaker Used:**
- **OOB Verification Performed:**
- **Escalation Triggered:**
- **Operator Removed from Loop:** (if applicable)

### Outcome

- **Confirmed Attempt:** Yes / No
- **Compromise Prevented:** Yes / No
- **Notes:**

---

## Part 6: Drift Log

### Entry Template

- **Date / Time:**
- **Drift Type:** (fog, narrowing, confusion, emotional flooding)
- **Trigger:**
- **Boundary Distortion Present:** Yes / No
- **Verification Performed:** Yes / No
- **Resolution:**
- **Follow-Up Required:**

### Usage Notes

Log drift events as they occur. Review weekly for patterns. Use longitudinal data to identify:
- Recurring manipulation vectors
- High-risk channels or contexts
- Operators who may need additional support
- Protocol gaps requiring hardening

---

## Part 7: Verification Protocol Sheet

### Verification Steps

1. **Pause** — Break the emotional frame.
2. **Switch Channels** — Move to a known-good medium.
3. **Use Pre-Established Tokens:**
   - Passphrase
   - Physical token
   - Known-good phone number
4. **Confirm Intent:**
   - "What is the purpose of this request?"
   - "What is the expected outcome?"
5. **Document the Verification:**
   - Time
   - Method
   - Result

### Principles

- Verification is not suspicion.
- Verification protects both parties.
- Out-of-band confirmation defeats single-channel attacks.
- Known-good channels must be established *before* incidents occur.

---

## Part 8: Red-Flag Pattern Library

### Urgency Scripts

- "This must be done in the next 10 minutes."
- "We'll lose the deal if you don't act now."
- "I don't have time to explain — just do it."
- "The CEO is waiting."

### Affinity Scripts

- "Remember that joke from dinner?"
- "We're close — you can trust me."
- "I wouldn't ask if it wasn't important."
- "You're the only one I can count on."

### Authority Scripts

- "I'm calling on behalf of the CEO."
- "This is confidential and cannot be escalated."
- "Your manager approved this already."
- "Don't question this — it's above your pay grade."

### Confusion Scripts

- "The legal structure is complex; just follow my instructions."
- "I'll explain later — right now I need you to act."
- "The compliance requirements changed; this is the new process."

### Identity Mimicry Patterns

- Slightly off voice tone
- Overuse of insider references
- Avoidance of verification
- Unfamiliar communication channel for a familiar person
- Requests that don't match the person's usual behavior

---

## Part 9: Operator Posture Training Module

### Duration

45 minutes (facilitated session, live or recorded)

### Module 1: The Operator as Steward

- The operator protects system integrity
- Compliance is not enough — stewardship is the standard
- Verification is kindness, not suspicion
- The emotional layer is a security surface

### Module 2: Recognizing Drift

- Fog: "I can't think straight"
- Confusion: "This doesn't make sense"
- Narrowing: "I can only focus on this one thing"
- Flooding: "I'm overwhelmed"

### Module 3: Emotional-Layer SOC Thinking

- Indicators are signals, not personal failures
- Correlation means compromise
- Tier your response to indicator count
- Document everything

### Module 4: Circuit Breaker Practice

- Role-play: Urgency script
- Role-play: Affinity script
- Role-play: Identity disruption
- Practice using cues under pressure

### Module 5: Verification Rituals

- Establish known-good channels in advance
- Passphrases and tokens
- Multi-party confirmation for high-risk events
- Documentation as protection

### Module 6: Post-Incident Hardening

- Complete the Drift Log
- Complete the Incident Triage Form
- Participate in pattern review
- Update SOPs based on learnings

---

## Part 10: Escalation Ladder

A structured path from detection to recovery:

1. **Detection** — Operator notices drift or boundary distortion.
2. **Containment** — Operator uses a circuit breaker cue.
3. **Verification** — Out-of-band confirmation.
4. **Eradication** — Identify the manipulation vector.
5. **Recovery** — Restore operator baseline.
6. **Hardening** — Update protocols, cues, and verification rituals.

---

## Part 11: Pilot Models

### Pilot A: Support Team Drift Detection

- **Team size:** 5–15 agents
- **Duration:** 2–3 weeks
- **Artifacts:** Detection Card, Drift Log, Verification Protocol
- **Goal:** Detect emotional manipulation during customer escalations
- **Outcome:** Drift events logged, verification rituals practiced, 1–2 incidents triaged

### Pilot B: Engineering Escalation Hardening

- **Team size:** 3–8 engineers + 1 lead
- **Duration:** 2–3 weeks
- **Artifacts:** Detection Card, Incident Triage Form, Escalation Ladder
- **Goal:** Prevent boundary distortion during high-pressure internal escalations
- **Outcome:** Tiered response model applied to 1–2 incidents, SOP updated

### Pilot C: Onboarding Curriculum Integration

- **Team size:** HR + L&D + 1 operational lead
- **Duration:** 2–3 weeks
- **Artifacts:** Operator Posture Training, Red-Flag Pattern Library
- **Goal:** Integrate emotional-layer awareness into onboarding
- **Outcome:** Training delivered, feedback collected, curriculum updated

---

## Part 12: Case Study Write-Up Structure

Use this format to document successful implementations.

### Header

- Organization type
- Team involved
- Duration
- Artifacts used

### Background

- Problem statement
- Emotional-layer risks observed
- Why EIOC was selected

### Implementation

- Training delivered
- Artifacts deployed
- Events logged
- Incidents triaged

### Outcome

- Quantitative results (incidents prevented, stress reduction, verification compliance)
- Qualitative feedback (operator quotes, team lead observations)
- SOP changes
- Stewardship posture shift

### Appendix

- Artifacts delivered
- Engagement reproducibility notes

---

## Conclusion

EIOC treats the emotional layer as a security surface. It provides:

- Detection primitives for recognizing manipulation
- Tier escalation logic for structured response
- Operator protocols for maintaining boundaries
- Documentation templates for audit-grade compliance
- Training modules for building stewardship culture

This framework is freely available. Use it. Adapt it. Implement it.

For training, certification, and organizational integration support, contact the author.

---

## Conformance

Organizations may claim EIOC alignment if they implement the following core components:

1. **Primitives** — The seven emotional indicators are recognized and defined within organizational policy.
2. **Tier Model** — The five-level escalation structure is adopted for incident classification.
3. **Verification Protocol** — Out-of-band verification procedures are established and practiced.
4. **Documentation Artifacts** — Drift Logs and Incident Triage Forms are used to record emotional-layer events.
5. **Operator Posture Training** — Personnel receive training on stewardship posture, circuit breaker cues, and drift recognition.

Partial implementation is acceptable during pilots. Full conformance requires all five components.

Organizations seeking formal certification or audit support should contact the author.

---

## Related Resources

- EIOC Canonical Specification v0.9 — Hash Attestation (DOI: 10.5281/zenodo.18439343)
- EIOC Standards Crosswalk v1.0 — ISO, IEEE, W3C, ACM (DOI: 10.5281/zenodo.18444566)
- EIOC-NIST AI RMF Integration v1.0 (DOI: 10.5281/zenodo.18445989)

---

## Contact

**Author:** Narnaiezzsshaa Truong  
**Framework:** Emotional Indicators of Compromise (EIOC)  
**Consultancy:** Soft Armor Labs  
**Repository:** https://github.com/Narnaiezzsshaa/eioc

---

**END OF DOCUMENT**
