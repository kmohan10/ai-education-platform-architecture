# 1. Purpose

### 1.1. Purpose

The Product Lexicon establishes the authoritative semantic vocabulary of the AI Education Platform.

It serves as the constitutional authority for the platform's governed language by defining the canonical concepts, relationship types, and semantic conventions used throughout the repository.

The Product Lexicon answers one constitutional question:

> **What language is legitimate?**

Every architectural model, research artifact, Architecture Decision Record (ADR), design document, and implementation shall use the concepts and relationship types defined by the Product Lexicon rather than introducing independent terminology.

This ensures semantic consistency, reduces ambiguity, and enables knowledge to evolve without fragmentation while providing a stable foundation for future reasoning systems.

### 1.2. Scope

The Product Lexicon governs the semantic vocabulary used throughout the AI Education Platform repository.

Specifically, it defines:

- The authoritative catalog of concepts used across the Product, Educational Models, and Platform layers.
- The controlled catalog of semantic relationship types that may be used to relate concepts.
- The canonical definitions, identifiers, and usage guidance for every concept and relationship.
- The semantic conventions that ensure consistent interpretation across all architectural artifacts.

The Product Lexicon does not define:

- Behavioral or causal interactions between concepts (Educational Concept Model).
- Internal representations of learner cognition (Learner Cognitive Model).
- Platform implementation or data structures.

### 1.3. Objectives

The objectives of the Product Lexicon are to:

- Establish a single, authoritative semantic vocabulary for the platform.
- Eliminate ambiguity through precise and governed definitions of concepts and relationships.
- Promote consistent terminology across governance, research, architecture, and implementation artifacts.
- Provide a controlled semantic foundation upon which conceptual, cognitive, instructional, and platform models can be constructed.
- Enable architectural knowledge to evolve while preserving semantic stability through permanent identifiers and governed terminology.
- Support future automation, knowledge management, reasoning systems, and AI capabilities by providing a machine-consistent semantic foundation.

# 2. Semantic Governance Principles

### 2.1. Authoritative Definition Principle

Every concept and relationship shall have one authoritative definition maintained within the Product Lexicon. All architectural artifacts shall reference that definition rather than redefining it.

### 2.2. Controlled Vocabulary Principle

Only concepts and relationship types defined in the Product Lexicon may be introduced into architectural artifacts. New terminology shall be added to the Lexicon before being used elsewhere.

### 2.3. Permanent Identity Principle

Every concept and relationship shall be assigned a permanent unique identifier. Identifiers are immutable and remain stable even if names, definitions, or classifications evolve over time.

### 2.4. Semantic Consistency Principle

The same concept shall always be expressed using its canonical name and identifier throughout the repository. Alternative names, synonyms, and historical terminology shall be explicitly governed rather than used interchangeably.

### 2.5. Separation of Semantic and Behavioral Knowledge Principle

The Product Lexicon defines concepts and their semantic relationships. Behavioral, causal, and dynamic interactions between concepts belong to the Educational Concept Model and shall not be represented within the Product Lexicon.

### 2.6. Evolution Without Fragmentation Principle

The Product Lexicon shall evolve through controlled refinement while preserving semantic continuity. Concepts may be extended, clarified, or deprecated, but changes shall not create ambiguity or fragment the repository's shared language.

# 3. Role within the Architecture

### 3.1. Architectural Position

The Product Lexicon serves as the semantic foundation of the architecture.

It occupies the constitutional layer between the Product Constitution and the Semantic Knowledge Architecture.

The Product Constitution establishes the platform's immutable principles.

The Product Lexicon establishes the governed language through which those principles are expressed.

The Semantic Knowledge Architecture governs the canonical representation of that language.

Together, the Product Lexicon and the Semantic Knowledge Architecture establish the platform's Canonical Semantic Model.

Every downstream architectural artifact inherits this semantic foundation and shall consume the canonical concepts and relationship types defined by the Product Lexicon rather than introducing independent terminology.

### 3.2. Dependencies

- **Product Constitution** The Lexicon uses the principle defined in the Product Constitution to establish the terms and their purpose.

### 3.3. Downstream Consumers

The Product Lexicon provides the authoritative semantic foundation for all downstream architectural artifacts. Every consumer shall use the canonical concepts, identifiers, and relationship types defined by the Product Lexicon rather than introducing independent terminology.

Downstream consumers inherit the canonical concepts and relationship types established by the Product Lexicon.

They may compose, organize, interpret, or operationalize those concepts within their own constitutional responsibilities, but they shall not redefine the canonical semantic vocabulary.

**Direct Consumers**

The following architectural artifacts directly consume the concepts and relationship types defined by the Product Lexicon as part of their own semantic foundation:

- **Product Vision** — Uses the canonical vocabulary to describe the desired future state of the platform.
- **Product Positioning** — Uses the canonical vocabulary to communicate the platform's unique value proposition.
- **Educational Concept Model** — Defines the behavioral and causal interactions between concepts defined in the Product Lexicon.
- **Learner Cognitive Model** — Describes learner cognition using the concepts defined in the Product Lexicon.
- **Educational Knowledge Model** — Represents instructional knowledge using the concepts and semantic relationships defined in the Product Lexicon.
- **Teaching DNA** — Encodes instructional expertise using the canonical educational vocabulary.
- **Instruction Model** — Composes learning experiences using concepts defined in the Product Lexicon.
- **Instructional Intelligence Platform** — Operationalizes instructional knowledge using the governed semantic model.
- **AI Agent Architecture** — Implements platform capabilities using the canonical semantic vocabulary established by the Product Lexicon.

**Indirect Consumers**

The following artifacts and systems indirectly rely on the Product Lexicon through one or more downstream architectural models:

- **Architecture Decision Records (ADRs)**
- **Research artifacts**
- **User documentation**
- **Implementation repositories**
- **APIs and data models**
- **Knowledge repositories and knowledge graphs**
- **AI reasoning systems**
- **Future platform services**

### 3.4. Relationship to Other Architecture Artifacts

The Product Lexicon governs meaning.

The Semantic Knowledge Architecture governs the canonical representation of that meaning.

Together they establish the Canonical Semantic Model upon which Institutional Knowledge is constructed.

#### 3.4.1. Architectural Relationship Vocabulary (Version 1.0)

The architectural relationships defined in this section constitute the initial controlled vocabulary for describing relationships between architecture artifacts. As the repository evolves, this vocabulary may be refined, consolidated, extended, or deprecated based on practical usage and architectural experience. Any such changes shall preserve architectural consistency across the repository.

| Relationship           | Purpose                                                                       |
| ---------------------- | ----------------------------------------------------------------------------- |
| **GOVERNED_BY**        | Subject to governance, policies, and lifecycle defined by another artifact.   |
| **TRACKED_BY**         | Progress, maturity, or evolution is recorded by another artifact.             |
| **ESTABLISHED_BY**     | Receives its foundational principles or philosophy from another artifact.     |
| **CONSUMED_BY**        | Uses the concepts, definitions, or knowledge without extending them.          |
| **EXTENDED_BY**        | Builds additional knowledge while preserving upstream semantics.              |
| **REPRESENTED_BY**     | Expresses upstream knowledge in another architectural form or representation. |
| **COMPOSED_BY**        | Combines governed knowledge into larger structures or experiences.            |
| **OPERATIONALIZED_BY** | Converts architectural knowledge into executable capabilities.                |
| **IMPLEMENTED_BY**     | Realizes operational capabilities through software implementation.            |

### 3.5. Evolution and Stability

The Product Lexicon establishes the platform's authoritative semantic vocabulary and therefore serves as a long-lived architectural asset. While the Lexicon shall evolve as the platform, educational research, and architectural knowledge mature, its evolution shall preserve semantic continuity for all downstream consumers.

The Product Lexicon balances long-term stability with controlled evolution through the following principles.

**Stable Semantic Core**:
Core Canonical Concepts, Canonical Relationships, and Canonical Identities constitute the semantic foundation of the platform and shall remain stable over time.

Changes affecting the semantic meaning or identity of these foundational assets shall occur only through the formal governance process and require broad architectural consensus.

**Controlled Semantic Evolution**
The Lexicon shall evolve through the controlled introduction of new Concepts, Relationships, definitions, aliases, and metadata.

Evolution shall extend the semantic knowledge of the platform without introducing ambiguity, conflicting terminology, or fragmented representations of existing concepts.

**Backward Compatibility**

Wherever practical, changes to the Product Lexicon shall preserve compatibility with existing architectural artifacts.

When semantic changes cannot remain backward compatible, migration guidance and explicit deprecation strategies shall accompany the affected Concepts or Relationships.

**Versioned Semantic Knowledge**

Every approved change to the Product Lexicon shall be versioned and recorded as part of the repository's architectural history.

Version history shall preserve semantic traceability and support the long-term evolution of the platform's knowledge architecture.

# 4. Lexicon Governance

Lexicon Governance establishes the policies, processes, and responsibilities for governing the lifecycle of all Semantic Assets established by the Product Lexicon and represented by the Semantic Knowledge Architecture. Its purpose is to preserve the integrity, consistency, stability, and long-term evolution of the platform's Canonical Semantic Model.

**Semantic Asset**
A Semantic Asset is any governed artifact that contributes to the platform's Canonical Semantic Model by defining, organizing, identifying, representing, or governing semantic knowledge. Semantic Assets include Canonical Concepts, Canonical Relationships, Identity Standards, Taxonomies, Schemas, Domain Hierarchies, Modeling Rules, Governance Policies, and other semantic structures established by the Product Lexicon and the Semantic Knowledge Architecture.

### 4.1. Governance Philosophy

The Product Lexicon and the Semantic Knowledge Architecture together establish the semantic foundation of the AI Education Platform. Consequently, every Semantic Asset shall be governed to preserve the integrity, consistency, stability, and long-term evolution of the platform's Canonical Semantic Model.

Lexicon Governance establishes the policies, principles, and governance processes that govern the lifecycle of all Semantic Assets established by the Product Lexicon and represented by the Semantic Knowledge Architecture. Its purpose is to ensure that the platform's semantic knowledge evolves through deliberate architectural stewardship rather than uncontrolled growth.

Lexicon Governance is founded upon the following principles:

**Semantic Integrity**

Every Semantic Asset shall preserve a clear, precise, and unambiguous semantic meaning. Changes shall strengthen semantic clarity and shall never introduce conflicting definitions, duplicate concepts, or inconsistent interpretations.

**Stability Before Change**

Semantic stability shall be preferred over unnecessary modification. Existing Semantic Assets shall evolve only when there is clear architectural justification and demonstrable long-term benefit.

**Controlled Evolution**

The Canonical Semantic Model is expected to evolve as educational knowledge, architectural understanding, and platform capabilities mature. Such evolution shall occur only through the formal governance process and shall preserve semantic continuity for downstream consumers.

**Single Source of Semantic Truth**

Every Semantic Asset shall have one authoritative representation within the Canonical Semantic Model. Alternative definitions, duplicate semantic structures, or competing vocabularies shall not be introduced elsewhere in the repository.

**Repository-Wide Consistency**

All architectural artifacts, research documents, models, implementation assets, and future reasoning systems shall consume Semantic Assets from the Canonical Semantic Model rather than creating independent semantic representations.

**Long-Term Knowledge Preservation**

Semantic Assets represent enduring institutional knowledge. Governance shall preserve their identity, traceability, and historical evolution so that architectural knowledge remains understandable, reusable, and maintainable over time.

**Governed Representation**

Semantic Governance preserves the governed representation of meaning rather than creating meaning itself.

The Product Lexicon establishes authoritative meaning.

The Semantic Knowledge Architecture governs how that meaning is represented, identified, organized, and evolved within the Canonical Semantic Model.

### 4.2. Governance Authority

Lexicon Governance establishes the architectural responsibilities required to govern the platform's Semantic Assets throughout their lifecycle. These responsibilities are independent of organizational structure and may be fulfilled by individuals, teams, governance bodies, or future automated governance systems.

Governance responsibilities are intentionally separated to ensure that the proposal, review, approval, and maintenance of Semantic Assets remain independent, transparent, and architecturally consistent throughout their lifecycle.

The governance responsibilities are:

**Proposal Authority**

Responsible for proposing the creation, modification, deprecation, or retirement of Semantic Assets in accordance with the governance principles established by the Product Lexicon.

**Review Authority**

Responsible for reviewing proposed changes for semantic correctness, architectural consistency, governance compliance, and downstream impact.

**Approval Authority**

Responsible for authorizing changes that satisfy the governance principles established by the Product Lexicon. Approval establishes a Semantic Asset as an authoritative part of the Canonical Semantic Model.

**Maintenance Authority**

Responsible for preserving the integrity, consistency, version history, and lifecycle of approved Semantic Assets after their incorporation into the Canonical Semantic Model.

These governance responsibilities represent architectural roles rather than organizational positions. A single individual, team, governance body, or future automated governance system may fulfill one or more responsibilities, provided the independence and integrity of the governance process are preserved.

### 4.3. Review Process

The Review Process provides a structured evaluation of proposed changes to Semantic Assets before they are submitted for approval. Its purpose is to ensure that every proposed change satisfies the governance principles established by the Product Lexicon and preserves the integrity, consistency, and long-term stability of the Canonical Semantic Model.

Every proposal shall undergo an independent architectural and semantic review before approval. The review process evaluates the proposed change from multiple perspectives to ensure that it strengthens the semantic knowledge of the platform without introducing ambiguity, inconsistency, or unintended downstream impact.

The Review Process shall evaluate, as applicable:

**Semantic Review**

Determines whether the proposed Semantic Asset has a clear, precise, and unambiguous meaning that is consistent with the existing Canonical Semantic Model.

**Architectural Review**

Evaluates the proposal for consistency with the Product Constitution, Product Lexicon, Semantic Knowledge Architecture, and other governed architectural artifacts.

**Consistency Review**

Ensures that the proposal does not introduce duplicate Concepts, conflicting terminology, overlapping semantic meaning, or inconsistent representations.

**Impact Analysis**

Assesses the potential impact of the proposed change on existing Semantic Assets, downstream architectural artifacts, implementation repositories, knowledge graphs, reasoning systems, and other consumers of the Canonical Semantic Model.

**Governance Compliance Review**

Verifies that the proposal complies with the governance principles, Identity Standards, Semantic Taxonomy, Canonical Semantic Schemas, Modeling Rules, and other applicable governance requirements.

Upon completion of the Review Process, the proposal shall be accompanied by a documented review recommendation indicating whether the proposed Semantic Asset is accepted for approval, revision required, or rejected.

### 4.4. Approval Process

The Approval Process authorizes the incorporation of reviewed Semantic Assets into the Canonical Semantic Model. Its purpose is to ensure that only proposals satisfying the governance principles established by the Product Lexicon become authoritative components of the platform's semantic knowledge.

Only proposals that have successfully completed the Review Process shall be eligible for approval. Approval confirms that the proposed Semantic Asset is architecturally sound, semantically consistent, governance compliant, and suitable for long-term inclusion within the Canonical Semantic Model.

The Approval Process shall verify that the proposal:

**Semantic Integrity**

Preserves the clarity, precision, and uniqueness of the platform's semantic knowledge.

**Architectural Consistency**

Remains consistent with the Product Constitution, Product Lexicon, Semantic Knowledge Architecture, and other governed architectural artifacts.

**Governance Compliance**

Complies with the Identity Standards, Semantic Taxonomy, Canonical Semantic Schemas, Modeling Rules, and all other applicable governance requirements.

**Long-Term Sustainability**

Supports the long-term evolution of the Canonical Semantic Model without introducing unnecessary complexity, semantic fragmentation, or architectural instability.

Upon approval, the proposed Semantic Asset becomes an authoritative part of the Canonical Semantic Model and shall be incorporated into the appropriate governed semantic artifacts. The approval decision shall be recorded as part of the repository's architectural history and become subject to the lifecycle management and versioning processes defined by Lexicon Governance.

### 4.5. Change Management

The Change Management process governs the controlled evolution of Semantic Assets throughout their lifecycle. Its purpose is to ensure that the Canonical Semantic Model remains internally consistent, architecturally coherent, and capable of evolving without compromising semantic integrity or long-term stability.

All changes to Semantic Assets shall follow the governance responsibilities and processes established by the Product Lexicon. No Semantic Asset shall be created, modified, deprecated, or retired outside the governed change management process.

### 4.5.1. Types of Change

Changes to Semantic Assets are classified according to the nature of the information being modified. This distinction ensures that changes affecting the semantic meaning of the Canonical Semantic Model receive an appropriate level of governance while allowing routine administrative updates to be managed efficiently.

**Semantic Change**

A Semantic Change modifies the meaning, interpretation, identity, classification, or semantic relationships of a Semantic Asset. Such changes affect the Canonical Semantic Model and may influence downstream architectural artifacts, knowledge representations, reasoning systems, or platform behavior.

Examples of Semantic Changes include:

- Introducing a new Canonical Concept
- Introducing a new Canonical Relationship
- Renaming a Canonical Name
- Modifying a Canonical Definition
- Changing a Concept Category
- Changing a Relationship Category
- Introducing, modifying, or deprecating Aliases
- Introducing or deprecating Deprecated Names
- Introducing, modifying, or removing Canonical Relationships
- Modifying the Purpose
- Modifying the Scope

All Semantic Changes shall undergo the complete governance process, including Proposal, Review, Approval, and subsequent lifecycle management.

**Metadata Change**

A Metadata Change modifies the governance or administrative information associated with a Semantic Asset without altering its semantic meaning or canonical identity. Metadata Changes support the ongoing management and traceability of Semantic Assets while preserving semantic continuity.  Metadata Changes shall be limited to Governance Metadata and shall not modify the Identity Profile, Semantic Profile, or governed Relationships of a Semantic Asset.

Examples of Metadata Changes include:

- Updating Version information
- Changing Review Status
- Updating Maintained By
- Recording the Last Modified date
- Updating the Origin Artifact
- Correcting administrative notes or references
- Recording First Introduced date

Metadata Changes shall preserve the semantic meaning, canonical identity, and governed relationships of the affected Semantic Asset. They shall be managed through the governance process appropriate to their impact but shall not require semantic re-evaluation unless the underlying semantic knowledge is also affected.

### 4.5.2. Lifecycle Activities

**Creation**

Introduces new Semantic Assets that extend the Canonical Semantic Model while preserving semantic consistency with existing knowledge.

**Modification**

Refines existing Semantic Assets to improve clarity, precision, or architectural consistency without unnecessarily disrupting downstream consumers.

**Extension**

Expands existing Semantic Assets through the controlled addition of semantic knowledge while preserving their canonical identity and established meaning.

(I deliberately separated Extension from Modification. We have often discussed that knowledge grows without necessarily changing the original concept.)

**Deprecation**

Marks Semantic Assets that should no longer be used while preserving their historical identity, traceability, and backward compatibility.

Deprecated Semantic Assets shall remain documented until formally retired.

**Retirement**

Removes deprecated Semantic Assets from active use following an approved governance process.

Retired Semantic Assets shall preserve their historical record and canonical identity within the repository.

**Migration**

Provides guidance for transitioning downstream consumers from deprecated or superseded Semantic Assets to their approved replacements. Migration shall preserve semantic continuity wherever practical.

Every change to a Semantic Asset shall preserve the integrity, traceability, and long-term continuity of the Canonical Semantic Model. Evolution shall strengthen the semantic knowledge of the platform rather than fragment it.

### 4.6. Versioning

Versioning preserves the history, traceability, and evolution of Semantic Assets throughout their lifecycle. Its purpose is to ensure that the Canonical Semantic Model evolves through controlled, transparent, and auditable changes while maintaining semantic continuity for all downstream consumers.

Every approved Semantic Change and Metadata Change shall be recorded through the platform's versioning process. Version history shall preserve the rationale, timing, and governance context associated with each change, enabling architectural knowledge to remain understandable, traceable, and reproducible over time.

### 4.6.1. Version Numbering

Version Numbering establishes the controlled versioning scheme used to identify the evolution of Semantic Assets throughout their lifecycle. Its purpose is to provide a consistent, traceable, and auditable mechanism for recording changes to the Canonical Semantic Model while preserving semantic continuity for all downstream consumers.

Every Semantic Asset shall possess a Semantic Knowledge Version Identifier using the following format:

SM-Major.Minor.Patch

where:

- **SM** denotes a Semantic Knowledge Version.
- **Major** represents significant Semantic Changes affecting the Canonical Semantic Model.
- **Minor** represents backward-compatible Semantic Changes that extend or refine existing Semantic Assets.
- **Patch** represents Metadata Changes or other non-semantic updates that preserve the semantic meaning of the affected Semantic Asset.

Version numbers shall evolve according to the following principles:

**Major Version**

A Major Version shall be assigned when a Semantic Change significantly affects the Canonical Semantic Model or requires downstream architectural consumers to reassess or migrate their semantic representations.

Examples include:

- Introducing major architectural changes to the Canonical Semantic Model.
- Significant modifications to Canonical Concepts or Canonical Relationships.
- Changes that materially affect semantic interpretation or architectural understanding.

Example:

SM-1.0.0  →  SM-2.0.0

**Minor Version**

A Minor Version shall be assigned when Semantic Knowledge is extended or refined while preserving backward compatibility with existing Semantic Assets.

Examples include:

- Introducing new Canonical Concepts.
- Introducing new Canonical Relationships.
- Refining Canonical Definitions.
- Extending Concept Categories or Relationship Categories.
- Introducing governed aliases.

Example:

SM-2.0.0  →  SM-2.1.0

**Patch Version**

A Patch Version shall be assigned when Metadata Changes or other administrative updates occur without modifying the semantic meaning, identity, or governed relationships of the affected Semantic Asset.

Examples include:

- Updating Version information.
- Updating Review Status.
- Updating Maintained By.
- Recording Last Modified.
- Updating Origin Artifact.
- Correcting administrative references.

Patch Versions shall never modify the Identity Profile, Semantic Profile, or governed Relationships of a Semantic Asset.

Example:

SM-2.1.0  →  SM-2.1.1

The Semantic Knowledge Version identifies the current governed state of a Semantic Asset. The version number reflects the cumulative evolution of both Semantic Changes and Metadata Changes, while the Change Type defined in Section 4.5 records the nature of each individual change.

### 4.6.2 Version History

Version History preserves the complete historical evolution of every Semantic Asset. Its purpose is to ensure that the Canonical Semantic Model remains transparent, traceable, and reproducible throughout its lifecycle.

Every Semantic Asset shall maintain a governed Version History recording all approved changes following their incorporation into the Canonical Semantic Model.

Each Version History entry shall record, as applicable:

- Semantic Knowledge Version
- Date of Change
- Change Type (Semantic Change or Metadata Change)
- Summary of Change
- Governance Decision
- Approval Reference
- Supporting Rationale

Version History shall preserve:

**Semantic Traceability**

The complete semantic evolution of every Concept and Relationship, including changes to identity, definitions, classifications, relationships, and governance.

**Governance Traceability**

The governance history associated with every approved change, including review outcomes, approval decisions, and supporting architectural rationale.

**Historical Preservation**

Previous versions shall remain part of the platform's institutional knowledge and shall not be removed following subsequent revisions, deprecation, or retirement.

**Architectural Continuity**

Version History shall enable downstream architectural artifacts, implementation repositories, knowledge graphs, and reasoning systems to understand both the current and historical semantic representations of a Semantic Asset.

**Change Transparency**

Every approved change shall be accompanied by sufficient governance information to explain what changed, why the change was made, when it became effective, and under which governance process it was approved.

**Backward Compatibility**

Where practical, Semantic Changes shall preserve compatibility with existing architectural artifacts, implementation repositories, and knowledge consumers. When compatibility cannot be maintained, appropriate migration guidance shall accompany the affected Semantic Assets.

A typical Version History entry may include the following information:

Semantic Knowledge Version Date Change Type Summary Approval Reference
SM-1.0.0 YYYY-MM-DD Initial Release Initial Canonical Definition LG-001
SM-1.1.0 YYYY-MM-DD Semantic Change Refined Definition and Scope LG-014
SM-1.1.1 YYYY-MM-DD Metadata Change Updated Review Status LG-015

Version History forms part of the platform's institutional knowledge and shall be preserved as an integral component of the Canonical Semantic Model.

The semantic governance principles established by the Product Lexicon are realized through the Semantic Knowledge Architecture defined in 003a_Semantic_Knowledge_Architecture.md.

Together these constitutional artifacts establish the platform's Canonical Semantic Model, providing the governed semantic foundation upon which Institutional Knowledge, Knowledge Models, Reasoning Models, and future platform capabilities are constructed.
