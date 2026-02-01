# EIOC Case Study #1

## Mid-Size SaaS Company — Customer Support Team

**Use Case:** Preventing emotional-layer compromise during high-pressure customer escalations  
**Duration:** 3 weeks  
**Team:** 12 agents + 1 team lead  
**Artifacts Used:** Detection Card, Verification Protocol Sheet, Incident Triage Form, Drift Log

---

## Background

A 300-person SaaS company experienced a pattern of emotionally manipulative escalation calls targeting their customer support team. Attackers impersonated frustrated customers, using urgency, anger, and familiarity to pressure agents into:

- Bypassing verification
- Issuing unauthorized refunds
- Granting account access
- Escalating to engineering without protocol

The company had strong technical controls but no emotional-layer detection.

They engaged the EIOC author to pilot the framework with a small support pod (12 agents + 1 team lead).

---

## Implementation

### Week 1 — Baseline & Training

Agents received:
- The EIOC Detection Card
- The Verification Protocol Sheet
- A 45-minute Operator Posture Training session

Agents were taught:
- How to recognize drift
- How to name boundary distortion
- How to use circuit breaker cues
- How to switch channels for verification

Agents began logging drift events in the Drift Log.

### Week 2 — Live Usage

Agents used the Detection Card during live calls.

Within 5 days, they documented:
- 14 drift events
- 6 boundary distortions
- 3 identity anomalies
- 2 multi-indicator events

Two incidents were escalated using the Incident Triage Form, both involving:
- Urgency pressure
- Emotional flooding
- Identity inconsistency

In both cases, the Verification Protocol prevented unauthorized actions.

### Week 3 — Pattern Recognition

The team lead reviewed Drift Logs and Triage Forms with the EIOC author.

A pattern emerged: **Attackers were using emotional urgency to bypass verification.**

Agents reported sensations like:
- "I felt rushed."
- "I couldn't think clearly."
- "They sounded familiar but I couldn't place them."

These were classic EIOC primitives: drift, fog, affinity pretexting.

The team lead was guided through interpreting the patterns using EIOC tier logic.

---

## Outcome

### Quantitative Results

| Metric | Result |
|--------|--------|
| Unauthorized refunds during pilot | **0** |
| Unauthorized account escalations | **0** |
| Suspicious calls caught before action | **100%** |
| Reduction in agent stress reports | **40%** |
| New verification steps added to SOPs | **2** |

### Qualitative Feedback

**Agents reported:**

> "I finally know what to do when I feel pressured."

> "I didn't realize confusion was a signal."

> "The circuit breaker cues saved me twice."

> "This is the first time emotional manipulation felt like a security issue, not a personal failure."

**Team lead reported:**

> "We've never had a framework that explains what operators *feel* during attacks."

> "EIOC gave us language, structure, and confidence."

> "This is the missing layer in our security program."

---

## Artifacts Delivered

| Artifact | Description |
|----------|-------------|
| Detection Card | One-page quick reference for recognizing emotional compromise |
| Verification Protocol Sheet | Repeatable OOB verification ritual |
| Incident Triage Form | Structured documentation for emotional-layer incidents |
| Drift Log | Longitudinal record of drift events |
| Operator Posture Training | 45-minute facilitated session |
| Tier Interpretation Session | 1-hour consulting session with team lead |

---

## Reproducibility Notes

This pilot model can be replicated with:

- **Team size:** 5–15 agents
- **Duration:** 2–3 weeks
- **Prerequisites:** None (EIOC is self-contained)
- **Integration:** Works alongside existing security controls

---

## Related Resources

- [EIOC Implementation Starter Kit](../implementation-starter-kit.md)
- [EIOC Standards Crosswalk](../standards-crosswalk.md)
- [EIOC-NIST AI RMF Mapping](../nist-ai-rmf-mapping.md)

---

## Contact

**Author:** Narnaiezzsshaa Truong  
**Framework:** Emotional Indicators of Compromise (EIOC)  
**Consultancy:** Soft Armor Labs

For training, certification, and organizational integration support, contact the author.
