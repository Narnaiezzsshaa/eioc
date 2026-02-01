# EIOC Standards Crosswalk: Mapping Emotional-Layer Governance to ISO, IEEE, W3C, and ACM

**Author:** Narnaiezzsshaa Truong  
**Version:** 1.0  
**Date:** January 31, 2026  
**License:** CC BY 4.0

---

## Abstract

Global standards bodies—including ISO, IEEE, W3C, and ACM—identify human factors, autonomy protection, and anti-manipulation safeguards as essential components of secure and ethical system design. However, none of these frameworks specify mechanisms for detecting emotional-layer compromise or operationalizing human-layer controls. The Emotional Indicators of Compromise (EIOC) framework provides the missing instrumentation: a structured set of emotional-layer detection primitives, correlation logic, and operator protocols that convert ethical mandates into measurable security surfaces. This crosswalk maps EIOC primitives to the relevant clauses and principles across ISO, IEEE, W3C, and ACM, demonstrating how EIOC completes the governance stack by supplying the operational layer required for effective implementation of human-factor controls.

---

## Introduction

Global standards bodies—including ISO, IEEE, W3C, and ACM—consistently emphasize the importance of human factors, autonomy protection, anti-manipulation safeguards, and ethical system behavior. Across these frameworks, the human operator is recognized as a critical point of vulnerability and responsibility. However, none of these standards specify how to detect, measure, or respond to violations of these principles at the emotional layer.

The Emotional Indicators of Compromise (EIOC) framework addresses this gap by providing a structured set of emotional-layer detection primitives, correlation logic, and operator protocols. EIOC does not replace existing standards; it operationalizes the human-layer commitments they require but do not define. It transforms abstract ethical mandates into measurable security surfaces, enabling organizations to detect emotional manipulation, boundary distortion, cognitive fog, and identity disruption as first-class security events.

This crosswalk maps EIOC primitives to the relevant clauses, principles, and guidelines across ISO, IEEE, W3C, and ACM. It demonstrates how EIOC completes the governance stack by supplying the missing emotional-layer instrumentation required for effective implementation of human-factor controls.

---

## Standards Crosswalk Matrix

### Emotional Drift

**ISO (27001, 31000):**  
*Alignment:* Human factors, awareness, competence, and behavior are acknowledged as risk vectors (ISO 27001: 6.1, 7.2, 7.3, 8.2).  
*EIOC adds:* A concrete taxonomy of drift states (fog, narrowing, disorientation) and treats them as measurable security signals rather than "user error."

**IEEE (7000 series):**  
*Alignment:* IEEE 7000 ethical design processes recognize human impact and cognitive burden but do not define drift as a first-class construct.  
*EIOC adds:* A formal "drift" primitive that can be monitored and used as a design constraint.

**W3C (WCAG, anti-manipulation):**  
*Alignment:* WCAG 2.x/3.0 address cognitive accessibility and comprehension load.  
*EIOC adds:* Adversarial drift detection—recognizing when interfaces or flows induce fog as a manipulation vector.

**ACM Code of Ethics:**  
*Alignment:* "Avoid harm" and "contribute to human well-being" include psychological harm.  
*EIOC adds:* An operational way to detect when systems are causing emotional harm via drift, not just when harm is conceptually prohibited.

---

### Boundary Distortion

**ISO (27001, 31000):**  
*Alignment:* ISO 27001 leadership, culture, and access control clauses assume clear boundaries but don't define emotional boundary erosion.  
*EIOC adds:* A vocabulary and detection logic for when operators are pressured to bypass or collapse boundaries ("just this once," "don't escalate").

**IEEE (7000 series):**  
*Alignment:* IEEE 7000/7001 discuss value alignment and transparency but not emotional boundary manipulation.  
*EIOC adds:* A governance lens for when system behavior or prompts are designed to erode user/operator boundaries.

**W3C (WCAG, anti-manipulation):**  
*Alignment:* W3C patterns and anti-dark-pattern work touch on deceptive flows.  
*EIOC adds:* Explicit recognition of boundary distortion as a dark-pattern class at the emotional layer, not just UI.

**ACM Code of Ethics:**  
*Alignment:* ACM prohibits deceptive or coercive practices.  
*EIOC adds:* A diagnostic tool to identify when professional boundaries are being manipulated, not just a rule that they must not be.

---

### Pressure-Based Credentialing

**ISO (27001, 31000):**  
*Alignment:* ISO 27001 covers phishing, BEC, and social engineering as risks but frames them in terms of content and channel.  
*EIOC adds:* The principle "urgency is not a credential" and a formal recognition that time pressure and authority pressure are authentication impersonators.

**IEEE (7000 series):**  
*Alignment:* IEEE ethics work warns against manipulative system behavior but doesn't model urgency as a pseudo-credential.  
*EIOC adds:* A design constraint: systems must not rely on pressure as a substitute for verifiable trust.

**W3C (WCAG, anti-manipulation):**  
*Alignment:* W3C anti-dark-pattern efforts flag countdown timers and forced flows.  
*EIOC adds:* A generalized pattern: any induced urgency that bypasses verification is an emotional indicator of compromise.

**ACM Code of Ethics:**  
*Alignment:* ACM's "avoid harm" and "be honest and trustworthy" forbid coercion.  
*EIOC adds:* A way to operationalize this by flagging pressure-based flows as violations of ethical authentication.

---

### Identity Disruption

**ISO (27001, 31000):**  
*Alignment:* ISO 27001/27002 address identity, access management, and impersonation, but primarily at the technical layer.  
*EIOC adds:* Emotional-layer identity disruption (deepfakes, voice mimicry, relational pretexting) as a distinct class of compromise.

**IEEE (7000 series):**  
*Alignment:* IEEE 7001 transparency and 7003 bias mitigation touch identity representation but not emotional identity mimicry.  
*EIOC adds:* A threat model for identity disruption that includes emotional familiarity and relational cues.

**W3C (WCAG, anti-manipulation):**  
*Alignment:* W3C identity and privacy work focuses on data and representation.  
*EIOC adds:* Detection of when identity cues in interfaces (avatars, names, tones) are being used to emotionally spoof trust.

**ACM Code of Ethics:**  
*Alignment:* ACM forbids deceptive identity use.  
*EIOC adds:* A structured way to recognize when identity is being emotionally spoofed, not just technically misrepresented.

---

### Cognitive Fog

**ISO (27001, 31000):**  
*Alignment:* ISO risk and awareness clauses acknowledge human error and overload but don't treat fog as an attack surface.  
*EIOC adds:* Fog as a first-class indicator of compromise—if the operator "can't think straight," the system treats that as a security event.

**IEEE (7000 series):**  
*Alignment:* IEEE 7000 recognizes cognitive burden but not adversarial induction of fog.  
*EIOC adds:* A requirement to design against induced confusion as a manipulation vector.

**W3C (WCAG, anti-manipulation):**  
*Alignment:* WCAG addresses clarity and comprehension.  
*EIOC adds:* A security-oriented view: when flows are designed or used to create confusion, that's an emotional exploit, not just bad UX.

**ACM Code of Ethics:**  
*Alignment:* ACM's duty to avoid harm includes mental overload.  
*EIOC adds:* A way to flag patterns that consistently produce fog as ethically suspect and operationally unsafe.

---

### Affinity Pretexting

**ISO (27001, 31000):**  
*Alignment:* ISO acknowledges social engineering but doesn't distinguish affinity-based pretexts from generic phishing.  
*EIOC adds:* A specific class of attack where unearned intimacy, shared jokes, or insider references are used to bypass controls.

**IEEE (7000 series):**  
*Alignment:* IEEE ethics work warns against manipulative personalization.  
*EIOC adds:* A precise pattern: affinity as a pretext, not just personalization, and its role in emotional compromise.

**W3C (WCAG, anti-manipulation):**  
*Alignment:* W3C UX and consent work touch on trust cues.  
*EIOC adds:* Recognition that "friendly" or "familiar" UI/personas can be weaponized as affinity pretexts.

**ACM Code of Ethics:**  
*Alignment:* ACM prohibits exploiting trust.  
*EIOC adds:* A structured way to detect when trust is being manufactured rather than earned.

---

### Correlated Compromise Logic

**ISO (27001, 31000):**  
*Alignment:* ISO risk management (27005, 31000) supports multi-factor risk analysis but doesn't define emotional indicators as correlated signals.  
*EIOC adds:* A tiered model where multiple emotional indicators combine into a "correlated compromise event."

**IEEE (7000 series):**  
*Alignment:* IEEE risk and ethics processes support multi-criteria analysis.  
*EIOC adds:* Emotional indicators as explicit criteria, with escalation thresholds.

**W3C (WCAG, anti-manipulation):**  
*Alignment:* W3C doesn't currently define multi-signal emotional compromise.  
*EIOC adds:* A way to treat combinations of UX patterns and emotional responses as a composite risk signal.

**ACM Code of Ethics:**  
*Alignment:* ACM speaks in principles, not tiers.  
*EIOC adds:* A structured escalation model for emotional harm and manipulation, enabling graded responses.

---

### Operator Posture (Stewardship)

**ISO (27001, 31000):**  
*Alignment:* ISO 27001 expects "competent, aware personnel" but doesn't define posture beyond compliance.  
*EIOC adds:* Stewardship as the operator stance—protecting system integrity, not merely following rules.

**IEEE (7000 series):**  
*Alignment:* IEEE 7000 emphasizes value alignment but not operator self-conception.  
*EIOC adds:* A defined role identity: the operator as steward, with emotional-layer responsibilities.

**W3C (WCAG, anti-manipulation):**  
*Alignment:* W3C focuses on user rights and protections, not operator posture.  
*EIOC adds:* A counterpart: those who run systems have an emotional-layer duty of care.

**ACM Code of Ethics:**  
*Alignment:* ACM defines professional responsibility but not emotional-layer stewardship.  
*EIOC adds:* A concrete posture and associated cues ("verification is kindness," etc.) as part of ethical practice.

---

## Conclusion

ISO, IEEE, W3C, and ACM each articulate strong normative positions on human autonomy, ethical system behavior, and the prevention of manipulation. Yet across all four bodies, the emotional layer remains uninstrumented. Human factors are acknowledged but not operationalized. Manipulation is prohibited but not detectable. Autonomy is protected in principle but not monitored in practice.

EIOC fills this structural gap by introducing a coherent emotional-layer detection system grounded in measurable primitives: drift, boundary distortion, pressure-based credentialing, identity disruption, cognitive fog, affinity pretexting, and correlated compromise logic. These primitives provide the missing operational substrate that allows existing standards to be implemented with fidelity.

By integrating EIOC with ISO, IEEE, W3C, and ACM frameworks, organizations gain the ability to detect emotional compromise events, respond with steward-grade operator protocols, and harden systems against adversarial emotional manipulation. EIOC does not extend these standards; it completes them.

---

## Related Identifiers

- EIOC Canonical Specification v0.9 — Hash Attestation (DOI: 10.5281/zenodo.18439343)

---

**END OF DOCUMENT**
