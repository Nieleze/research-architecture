# Nieleze Assessment Schema

## Purpose

This document defines how the Structural Risk Intelligence architecture is applied through structured assessments.

Assessments are applications of the broader research architecture. They do not constitute separate theoretical systems.

The assessment layer translates the architecture into structured examination of how organizations:

- detect emerging conditions
- interpret signals
- escalate concerns
- make decisions
- intervene
- contain or experience failure
- recover
- learn and adapt

The underlying analytical question is:

> **How do organizations detect, interpret, escalate, and act on emerging conditions before visible failure?**

---

## Assessment logic

The reference assessment pathway is:

    Condition
        ↓
    Signal
        ↓
    Recognition
        ↓
    Interpretation
        ↓
    Escalation
        ↓
    Decision
        ↓
    Intervention
        ↓
    Outcome
        ↓
    Recovery / Learning

This is a reference structure, not a deterministic sequence.

Conditions may influence multiple stages simultaneously.

Signals may be:

- absent
- weak
- suppressed
- fragmented
- misrecognized
- ambiguously interpreted
- delayed in escalation
- acted upon after intervention capacity has narrowed

Feedback may also operate from later stages back into earlier stages.

For this reason, assessment outputs should identify structural relationships and constraints rather than assume simple linear causality.

---

# Assessment applications

## 1. Structural Risk Snapshot

### Purpose

The Structural Risk Snapshot is a focused assessment of emerging-risk visibility and structural exposure.

It is intended to provide an early view of where an organization may be losing visibility, interpretive capacity, intervention time, or recovery capacity before visible failure occurs.

### Core questions

- What emerging conditions are present?
- What signals are visible?
- What signals may be weak, suppressed, or overlooked?
- Where does detection differ from recognition?
- How are signals being interpreted?
- Where may escalation thresholds be drifting?
- How much intervention time remains?
- Which barriers may contain or amplify the condition?
- What structural conditions may allow risk to accumulate?
- What recovery or adaptation capacity remains?

### Primary mechanisms

- `mechanism-001` — Signal Detection
- `mechanism-002` — Signal Suppression
- `mechanism-003` — Detection vs Recognition
- `mechanism-006` — Escalation Threshold Drift
- `mechanism-008` — Risk Visibility Horizon
- `mechanism-009` — Barrier Integrity
- `mechanism-010` — Recovery Window

### Primary analytical layers

- Organizational Sensing
- Interpretation
- Escalation
- Intervention Architecture
- Failure Dynamics
- Resilience & Adaptation

### Output

The Structural Risk Snapshot should identify:

1. visible and potentially invisible conditions;
2. relevant signals;
3. potential suppression or recognition gaps;
4. escalation constraints;
5. remaining intervention space;
6. barrier or containment conditions;
7. recovery capacity;
8. areas requiring deeper investigation.

---

# 2. Organizational Sensing Assessment

## Purpose

The Organizational Sensing Assessment examines how an organization detects, recognizes, interprets, escalates, and responds to emerging conditions.

It asks not simply whether information exists, but whether the organization can convert meaningful signals into timely understanding and action.

## Assessment dimensions

### Sensing

**Core question:**

> What are we noticing, and what are we missing?

Relevant mechanisms:

- `mechanism-001` — Signal Detection
- `mechanism-002` — Signal Suppression

Relevant concepts:

- `concept-009` — Organizational Sensing Modes
- `concept-010` — Signal Suppression Dynamics

---

### Recognition

**Core question:**

> Has the significance of the signal been recognized?

Relevant mechanism:

- `mechanism-003` — Detection vs Recognition

Relevant concepts:

- `concept-002` — Signal-to-Decision Gap
- `concept-009` — Organizational Sensing Modes
- `concept-006` — Structural Clarity

---

### Interpretation

**Core question:**

> What does the signal mean under actual organizational conditions?

Relevant mechanisms:

- `mechanism-004` — Interpretive Bottleneck
- `mechanism-005` — Interpretive Fragmentation

Relevant concepts:

- `concept-006` — Structural Clarity
- `concept-005` — Organizational Coherence Map
- `concept-007` — Interpretive Failure Governance Systems

---

### Escalation

**Core question:**

> When does the signal become actionable?

Relevant mechanism:

- `mechanism-006` — Escalation Threshold Drift

Relevant concepts:

- `concept-002` — Signal-to-Decision Gap
- `concept-008` — Governance Diagnostic Degradation

---

### Decision

**Core question:**

> Can the organization decide effectively before available options narrow?

Relevant mechanism:

- `mechanism-007` — Decision Compression

Relevant concepts:

- `concept-002` — Signal-to-Decision Gap
- `concept-006` — Structural Clarity
- `concept-011` — Adaptive Margin Architecture

---

### Intervention

**Core question:**

> Why does intervention arrive too late, or fail despite available safeguards?

Relevant mechanisms:

- `mechanism-008` — Risk Visibility Horizon
- `mechanism-009` — Barrier Integrity

Relevant concepts:

- `concept-011` — Adaptive Margin Architecture
- `concept-012` — Oversight Failure Convergence

---

### Recovery and Learning

**Core question:**

> Can experience become retained organizational capacity?

Relevant mechanisms:

- `mechanism-010` — Recovery Window
- `mechanism-011` — Organizational Learning

Relevant concepts:

- `concept-005` — Organizational Coherence Map
- `concept-011` — Adaptive Margin Architecture

---

# 3. Organizational Coherence Map

## Purpose

The Organizational Coherence Map examines relationships among:

- interpretation
- coordination
- responsibility
- information flow
- decision authority
- action

It focuses on whether distributed parts of an organization can maintain sufficient structural coherence for coordinated action.

## Core questions

- Do different organizational actors construct compatible interpretations?
- Where does information become fragmented?
- Where are responsibilities unclear or disconnected?
- Where are escalation pathways interrupted?
- Where can coordination degrade?
- Where does local optimization conflict with system-level visibility?
- Where can operational activity remain functional while structural coherence deteriorates?
- Where are governance structures becoming disconnected from operational reality?

## Primary mechanisms

- `mechanism-003` — Detection vs Recognition
- `mechanism-004` — Interpretive Bottleneck
- `mechanism-005` — Interpretive Fragmentation
- `mechanism-006` — Escalation Threshold Drift
- `mechanism-007` — Decision Compression
- `mechanism-011` — Organizational Learning

## Primary concepts

- `concept-005` — Organizational Coherence Map
- `concept-006` — Structural Clarity
- `concept-007` — Interpretive Failure Governance Systems
- `concept-008` — Governance Diagnostic Degradation

---

# Assessment dimensions

The common assessment vocabulary is:

| Dimension | Core question | Primary mechanism(s) |
|---|---|---|
| Sensing | What are we noticing — and what are we missing? | `mechanism-001`, `mechanism-002` |
| Recognition | Has the significance of the signal been recognized? | `mechanism-003` |
| Interpretation | What does the signal mean? | `mechanism-004`, `mechanism-005` |
| Escalation | When does the signal become actionable? | `mechanism-006` |
| Decision | Can the organization decide effectively under uncertainty? | `mechanism-007` |
| Intervention | Why does intervention arrive too late? | `mechanism-008`, `mechanism-009` |
| Recovery | Can sufficient recovery capacity remain available? | `mechanism-010` |
| Trust & Oversight | Who is responsible for understanding and acting on what is seen? | `mechanism-009`, `mechanism-011` |
| Organizational Learning | Does experience become structural adaptation? | `mechanism-011` |
| Organizational Coherence | Can distributed actors maintain sufficient shared understanding for coordinated action? | `mechanism-005`, `mechanism-006`, `mechanism-007` |

---

# Assessment output model

An assessment should not produce only a score or binary judgment.

The preferred output is a structured representation of:

1. **Observed condition**
2. **Relevant signal**
3. **Recognition state**
4. **Interpretive state**
5. **Escalation state**
6. **Decision constraint**
7. **Intervention horizon**
8. **Barrier condition**
9. **Recovery capacity**
10. **Learning/adaptation condition**
11. **Relevant structural mechanism(s)**
12. **Evidence and provenance**
13. **Uncertainty or evidence limitations**
14. **Areas requiring additional investigation**

This enables the assessment layer to connect directly to the research architecture.

---

# Assessment-to-architecture mapping

Assessments should reference canonical entities through stable identifiers.

For example:

    assessment observation
          ↓
    mechanism-002
          ↓
    concept-010
          ↓
    N22
          ↓
    canonical Nieleze publication

An assessment should not create an independent duplicate definition of a mechanism.

Where an assessment encounters a mechanism already represented in the repository, it should reference that canonical mechanism.

Where an assessment reveals a genuinely new mechanism or concept, that entity should first be evaluated for inclusion in the canonical ontology or mechanism schema.

---

# Evidence and provenance

Assessment findings should distinguish between:

- observed evidence
- interpretation
- structural inference
- hypothesis
- unresolved uncertainty

A structural assessment should not present an inferred mechanism as a directly observed fact unless the evidence supports that claim.

Where an assessment uses published Nieleze concepts or mechanisms, the corresponding source ID should be resolvable through:

`sources/references.csv`

---

# Relationship to cross-sector intelligence

Assessments may operate within a single domain or across domains.

When an assessment uses cross-sector transfer, it should identify the relevant mapping in:

`matrices/cross-sector-mapping.csv`

Cross-sector analogies should not be represented as universal equivalence.

The assessment should preserve domain-specific context while identifying the structural mechanism being examined.

---

# Relationship to the Structural Lens

The Structural Lens may expose assessment concepts and pathways as navigational surfaces.

The Lens should not imply that a discovery interface itself constitutes an assessment.

Where an assessment is substantive, the Lens should route users toward the relevant assessment application and authoritative Nieleze material.

Possible Lens pathways include:

    Concept
      ↓
    Mechanism
      ↓
    Assessment dimension
      ↓
    Relevant assessment
      ↓
    Canonical Nieleze source

and:

    Domain
      ↓
    Cross-sector mapping
      ↓
    Mechanism
      ↓
    Assessment application

---

# Assessment boundaries

Assessments are intended to support structural inquiry.

They should not be represented as:

- universal predictors
- deterministic failure forecasts
- replacements for domain-specific expertise
- substitutes for empirical investigation
- evidence that a specific failure will occur

Assessment outputs should reflect uncertainty where evidence is incomplete.

The architecture is concerned with identifying structural conditions that may increase, constrain, amplify, or reduce the capacity for timely detection, interpretation, escalation, action, recovery, and adaptation.

---

# Application principle

The assessment layer translates the broader Structural Risk Intelligence architecture into applied inquiry.

The central principle remains:

> The existence of information does not necessarily mean that an organization can recognize, interpret, escalate, and act on its significance before intervention space narrows.

Assessments therefore examine the pathway from emerging condition to organizational response rather than treating visible failure as the starting point of analysis.

---

# Architectural status

The assessment schema is an application layer of the Nieleze Structural Risk Intelligence architecture.

It should remain subordinate to:

- the canonical ontology
- the mechanism architecture
- the cross-sector mapping layer
- the provenance registry

Assessment-specific adaptations may be introduced without changing the canonical architecture unless they reveal a genuinely new structural entity.

---

# Primary source

https://www.nieleze.com/
