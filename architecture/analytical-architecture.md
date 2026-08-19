# Analytical Architecture

## Purpose

This document defines the analytical architecture represented by the Nieleze research artifact.

**Structural Risk Intelligence is the study of how organizations detect, interpret, escalate, and act on emerging conditions before visible failure.**

**Nieleze is the research and publication platform through which this body of work is developed, published, and applied.**

The repository is a structured research representation of the concepts, mechanisms, relationships, domains, assessments, and provenance underlying that architecture. It is designed to make the architecture inspectable, traceable, and machine-readable without requiring the repository to reproduce the full substantive corpus published on Nieleze.com.

The repository is not a duplicate website and is not intended to reproduce the complete Nieleze publication layer.

The architecture has three complementary surfaces:

1. **Nieleze.com** — authoritative substantive publication layer.
2. **GitHub research architecture** — versioned, machine-readable research artifact.
3. **Nieleze Structural Lens** — interactive interpretation and discovery layer over the structured artifact.

The Lens is a projection of the research artifact rather than an independent research corpus.

---

## Conceptual anchor

Structural Risk Intelligence provides the common analytical spine for the research architecture.

Its central concern is the organizational pathway from emerging condition to visible consequence:

    detect
       ↓
    interpret
       ↓
    escalate
       ↓
    act
       ↓
    before visible failure

This pathway is not treated as a deterministic sequence.

Conditions can be:

- missed
- suppressed
- misrecognized
- ambiguously interpreted
- fragmented across organizational boundaries
- delayed at escalation thresholds
- compressed during decision-making
- encountered after intervention capacity has narrowed
- contained by effective barriers
- allowed to propagate through failed barriers
- converted into organizational learning
- repeated when learning does not become adaptation

The architecture therefore studies not only failure itself, but the structural conditions that determine whether emerging conditions become visible, actionable, containable, recoverable, or recurrent.

---

## Architectural principle

The system is organized around the distinction between:

- **what exists in the research vocabulary**
- **how mechanisms operate**
- **where mechanisms are observed or applied**
- **how mechanisms relate across contexts**
- **how claims and mappings are sourced**
- **how users navigate the architecture**

The repository therefore separates:

- ontology
- mechanisms
- cross-sector mappings
- assessments
- provenance
- architectural interpretation
- Lens-facing structures

These layers should remain linked through stable identifiers rather than duplicated names or free-text references.

---

## Core entities

### Concepts

Concepts are named analytical entities in the Structural Risk Intelligence vocabulary.

Each canonical concept has a stable identifier in:

`ontology/concepts.csv`

Concept identifiers must remain stable even if the human-readable label, description, or publication location changes.

A concept may represent:

- a framework
- a core concept
- a structural concept
- a methodology
- an assessment construct
- another explicitly recognized analytical entity

Concepts should not be created merely because a phrase appears in a publication.

A recurring term becomes a canonical concept only when it has a defensible role in the research architecture.

---

### Mechanisms

Mechanisms describe processes through which organizational or systemic conditions change, propagate, degrade, constrain, amplify, contain, or feed back into one another.

Canonical mechanisms are represented in:

`mechanisms/signal-to-decision.csv`

Each mechanism has:

- stable ID
- macro stage
- pathway position
- mechanism class
- input state
- output state
- primary concept
- secondary concepts
- Lens territories
- structural role
- provenance

Mechanisms are not merely topics.

They are structural processes.

---

## Signal-to-decision pathway

The signal-to-decision architecture provides a reference pathway through which emerging conditions can move toward organizational action and recovery.

The current pathway is:

1. Sensing
2. Recognition
3. Interpretation
4. Escalation
5. Decision
6. Intervention
7. Recovery
8. Learning

The pathway is not assumed to be strictly linear.

Multiple mechanisms may operate within the same stage, and mechanisms may:

- branch
- interact
- bypass stages
- suppress downstream visibility
- compress decision time
- reduce recoverability
- feed back into earlier stages

`stage_order` therefore represents macro-stage position.

`path_position` represents the mechanism's current position in the reference pathway.

Neither field should be interpreted as proof that real-world systems always operate in a single deterministic sequence.

---

## Mechanism classes

Mechanism classes describe the primary structural behavior of a mechanism.

Current classes include:

- detection
- degradation
- recognition
- interpretive-constraint
- interpretive-fragmentation
- threshold-drift
- decision-compression
- temporal-window
- containment
- recovery-capacity
- feedback

Additional mechanism classes may be introduced when analytically justified.

Mechanism classes should describe structural behavior rather than sector-specific language.

---

## Structural roles

`structural_role` describes how a mechanism functions in relation to organizational conditions.

Examples include:

- initiates
- degrades
- transforms
- constrains
- fragments
- delays
- compresses
- narrows
- contains-or-fails
- determines
- feeds-back

Structural role is distinct from mechanism class.

A mechanism class answers:

> What kind of mechanism is this?

A structural role answers:

> What does it do in the architecture?

---

## Domains

Domains are application contexts, not separate theoretical systems.

Examples include:

- Healthcare Systems
- Finance & Decision Systems
- Aviation & Aerospace Safety
- Robotics & Automation Oversight
- Nuclear & High-Reliability Systems

Domains are represented in:

`matrices/cross-sector-mapping.csv`

A domain mapping does not imply that two sectors are equivalent.

The purpose of cross-sector analysis is to identify:

- recurring structural mechanisms
- analogous failure pathways
- transferable questions
- structural similarities
- meaningful differences in how mechanisms operate under different constraints

Cross-sector analysis must not collapse domain-specific context into a generic universal claim.

---

## Cross-sector transfer

A cross-sector mapping should distinguish the type of relationship between a mechanism and a domain expression.

Current mapping relations include:

- `direct`
- `analogous`
- `complementary`

### Direct

The domain expression closely corresponds to the canonical mechanism.

### Analogous

The domain expression exhibits a comparable structural pattern, but the mechanism should not be assumed to be identical in operational form.

### Complementary

The domain expression interacts with or informs the mechanism but should not be collapsed into it.

This distinction exists to prevent false equivalence across sectors.

---

## Analytical layers

The architecture currently organizes material into recurring analytical layers including:

### Organizational Sensing

How organizations detect, surface, suppress, absorb, recognize, or miss emerging conditions.

### Interpretation

How signals become meaningful or fail to become actionable knowledge.

### Escalation

How conditions cross, fail to cross, or drift across thresholds for formal attention and action.

### Decision Intelligence

How organizational decision processes respond to signals under uncertainty, compression, ambiguity, and competing demands.

### Intervention Architecture

How organizations use remaining response capacity, safeguards, controls, and intervention windows.

### Failure Dynamics

How initially bounded conditions propagate, interact, amplify, or cross containment boundaries.

### Resilience & Adaptation

How systems preserve operating capacity, recover, learn, and adapt.

### Trust & Oversight

How responsibility, supervision, human-machine relationships, governance, and oversight structures affect system behavior.

### Cross-Sector Intelligence

How structurally comparable mechanisms are identified across otherwise different domains.

These layers are analytical lenses rather than mutually exclusive categories.

A concept or mechanism may legitimately participate in more than one layer.

---

## Provenance architecture

Every substantive concept, mechanism, mapping, and assessment construct should be traceable to a stable source identifier where appropriate.

The canonical registry is:

`sources/references.csv`

A source record contains:

- stable source ID
- title
- source type
- source role
- canonical URL
- canonical path
- notes
- status

Other schemas should reference the source ID rather than repeatedly embedding URLs.

For example:

`source_id = N22`

should resolve through:

`sources/references.csv`

to the canonical publication:

`/interpretation-layer/signal-suppression-dynamics`

This creates a provenance chain:

    research entity
        ↓
    stable source ID
        ↓
    canonical Nieleze publication

The repository should avoid treating a URL itself as the identity of a research entity.

---

## Source roles

The provenance layer distinguishes different roles played by published material.

Examples include:

- Organization
- Architecture
- Applied systems
- Assessment
- Core concept
- Mechanism
- Structural model
- Structural concept
- Cross-sector architecture
- Cross-sector intelligence
- Methodology
- Strategic foresight
- Trust and oversight
- Interpretation layer
- Signal domain

Source role describes what the source contributes to the architecture.

It does not by itself establish originality, authorship, or intellectual priority.

---

## Canonical publication boundary

Nieleze.com remains the authoritative substantive publication layer.

The GitHub artifact should not attempt to reproduce the complete text of canonical publications.

The repository should instead represent:

- structured concepts
- mechanisms
- relationships
- mappings
- metadata
- provenance
- analytical architecture

The Lens should direct users to the relevant canonical publication when substantive explanation is required.

This preserves a useful separation:

    structured discovery
          ↓
    GitHub artifact
          ↓
    canonical Nieleze publication
          ↓
    substantive analysis

---

## Lens architecture

The Nieleze Structural Lens is an interface over the Structural Risk Intelligence research architecture.

It should consume or resolve against structured entities such as:

- concepts
- mechanisms
- territories
- relationships
- domains
- provenance records

The Lens should not become a second uncontrolled corpus.

A Lens result should ideally be traceable through:

    Lens surface
        ↓
    concept / mechanism / mapping
        ↓
    stable repository ID
        ↓
    source ID
        ↓
    canonical Nieleze publication

This makes discovery auditable.

---

## Lens territories

Lens territories are persistent thematic surfaces used to organize navigation and interpretation.

Current territories include:

- Error Pathway
- Organizational Sensing
- Structural Dependence
- Governance Failure
- Cross-Sector Analysis
- Ambiguity
- Escalation
- Organizational Learning
- Interpretation
- Human–Machine Oversight

Territory membership is many-to-many.

A mechanism or concept may belong to multiple territories when justified.

Territories should not become substitutes for analytical layers.

A territory is primarily an interface and discovery construct.

An analytical layer is a conceptual classification.

---

## Stable identifiers

Stable IDs are canonical references across the repository.

Examples:

- `concept-010`
- `mechanism-002`
- `mapping-001`
- `N22`

Human-readable names and URLs may change.

Stable IDs should change only when the underlying entity itself is determined to be a distinct entity.

Renaming an entity should not require changing its ID.

---

## Naming and slug policy

Human-readable labels should be clear and publication-compatible.

Slugs should:

- use lowercase
- use hyphens
- avoid unnecessary abbreviations
- remain stable where practical

Examples:

`signal-suppression`

`decision-compression`

`risk-visibility-horizon`

Slugs are interface identifiers, not canonical entity identity.

---

## Many-to-many relationships

Where one entity may relate to multiple concepts or territories, the current CSV convention is:

`|`

Example:

`concept-010|concept-002`

or:

`organizational-sensing|ambiguity|error-pathway`

Commas remain reserved for CSV field separation.

This convention must be retained unless the repository is migrated to a structured format such as JSON.

---

## Repository versus website

The repository and website serve different functions.

### Nieleze.com

Primary role:

- substantive publication
- explanatory content
- cases
- models
- applied analysis
- strategic interpretation
- authoritative public source material

### GitHub research architecture

Primary role:

- structured representation
- schema
- relationships
- provenance
- version history
- machine-readable research artifact

### Structural Lens

Primary role:

- exploration
- discovery
- relationship navigation
- query interpretation
- pathway exploration
- routing users to substantive material

The three surfaces should reinforce one another rather than duplicate one another.

---

## Versioning

Git history is the primary versioning mechanism for the research artifact.

Changes should normally be made by editing and committing the canonical file rather than creating multiple files such as:

- `concepts-v2.csv`
- `concepts-final.csv`
- `concepts-final-final.csv`

Historical versions remain available through Git commit history.

Schema-level changes may be recorded through a future repository manifest or schema version.

Schema versions should describe structural compatibility, not merely each individual edit.

---

## Validation principles

As the repository develops, validation should enforce at minimum:

1. Every referenced concept ID exists.
2. Every referenced mechanism ID exists.
3. Every referenced source ID exists.
4. Every domain source ID resolves to a source record.
5. Every canonical source URL is valid and intentionally curated.
6. Every Lens territory referenced by an entity is defined.
7. No duplicate stable IDs exist.
8. Slugs are unique within their entity type.
9. Required CSV fields are present.
10. Multi-value fields use the repository delimiter convention.
11. Cross-sector mappings identify their relationship type.
12. Provenance does not silently point to unrelated or generic pages.
13. Published entities do not rely on unpublished or missing source records.

Validation should eventually be automated through repository checks.

---

## Proprietary methodology boundary

The research artifact is not intended to publish the complete proprietary Nieleze methodology.

The repository may expose:

- public terminology
- public concepts
- public structural relationships
- public mechanisms
- public mappings
- public provenance
- public analytical architecture

The repository should not expose proprietary internal procedures unless intentionally published.

Examples of potentially proprietary material include:

- unpublished product methodology
- internal scoring logic
- proprietary decision rules
- unpublished calibration procedures
- internal synthesis procedures
- non-public assessment logic
- proprietary sequencing or operational playbooks

Publication of a structural vocabulary does not imply publication of all methods used to derive or apply that vocabulary.

Where a distinction is material, repository documentation should describe the public artifact as a representation of the published architecture rather than as a complete disclosure of the underlying methodology.

---

## Licensing and reuse

The repository should have an explicit license or rights statement.

The license should clearly distinguish:

1. rights granted over repository code and data
2. rights granted over original research content
3. rights and restrictions applying to the Nieleze website and publications
4. material that remains proprietary and unpublished

A repository license should not be interpreted as a blanket license to reproduce the complete Nieleze publication corpus or proprietary methodology.

The final repository should include a dedicated `LICENSE` or rights document appropriate to the intended reuse model.

Until that license is intentionally selected and committed, reuse rights should not be assumed beyond rights that apply by law.

---

## Canonical direction of authority

Where conflicts arise, the following order applies:

1. Current authoritative Nieleze publication
2. Current structured research artifact
3. Lens presentation

The Lens is an interface.

The GitHub repository is the structured artifact.

Nieleze publications are the substantive authority.

A change in Lens presentation should not silently alter the underlying research architecture.

A change in the research artifact should be traceable to its Git history and provenance.

A change in substantive published research may require corresponding updates to the artifact.

---

## Architectural invariants

The following principles should remain stable as the repository evolves:

### 1. Concepts are not mechanisms

A concept names or frames an analytical entity.

A mechanism describes behavior or process.

### 2. Domains are not theories

A domain is an application context.

It does not create a new theoretical architecture merely because the expression differs.

### 3. Mappings are not equivalence claims

Cross-sector mappings identify structural correspondence or useful transfer.

They do not assert that sectors are identical.

### 4. Provenance is not decoration

Sources should be resolvable and intentionally connected to the entities they support.

### 5. The Lens is not the corpus

The Lens should help users navigate the architecture without becoming an uncontrolled parallel publication system.

### 6. Stable IDs matter more than names

Names and URLs may evolve.

Entity identity should remain stable wherever the underlying entity remains the same.

### 7. Public architecture does not equal complete methodology disclosure

The repository may expose a public structural representation while proprietary methods remain unpublished.

### 8. Structural Risk Intelligence is the conceptual spine

Concepts, mechanisms, mappings, assessments, and Lens surfaces should remain intelligible as parts of the broader Structural Risk Intelligence architecture rather than becoming disconnected standalone artifacts.

---

## Intended end-state

The mature architecture should support the following chain:

    Nieleze
        ↓
    Structural Risk Intelligence
        ↓
    canonical concepts / mechanisms / relationships
        ↓
    cross-sector mappings
        ↓
    assessments / applications
        ↓
    Structural Lens territories
        ↓
    interactive exploration

The same architecture should be usable by:

- humans reading the repository
- the Structural Lens
- future APIs
- graph visualizations
- search and retrieval systems
- research tooling
- future analytical interfaces

The repository should therefore remain structured enough to support new interfaces without requiring the underlying research architecture to be rebuilt for each interface.
