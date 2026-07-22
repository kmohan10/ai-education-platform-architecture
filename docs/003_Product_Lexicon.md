# 1. Purpose

### 1.1. Purpose

The Product Lexicon establishes the authoritative semantic vocabulary of the AI Education Platform. It provides the canonical definitions of concepts and the governed relationship types used throughout the repository.

Every architectural model, research artifact, ADR, design document, and implementation shall use terminology and relationships defined by the Product Lexicon. This ensures semantic consistency, reduces ambiguity, and enables knowledge to evolve without fragmentation and while providing a stable foundation for future reasoning systems.

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

It sits between the Product Constitution and all downstream architectural models.

The Constitution establishes the platform's principles.

The Lexicon establishes the language used to express those principles.

Every subsequent architectural artifact depends upon this shared semantic foundation.

### 3.2. Dependencies

- **Product Constitution** The Lexicon uses the principle defined in the Product Constitution to establish the terms and their purpose.

### 3.3. Downstream Consumers

The Product Lexicon provides the authoritative semantic foundation for all downstream architectural artifacts. Every consumer shall use the canonical concepts, identifiers, and relationship types defined by the Product Lexicon rather than introducing independent terminology.

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

The Product Lexicon also provides the semantic foundation for:

- **Architecture Decision Records (ADRs)**
- **Research artifacts**
- **User documentation**
- **Implementation repositories**
- **APIs and data models**
- **Knowledge repositories and knowledge graphs**
- **AI reasoning systems**
- **Future platform services**

### 3.4. Relationship to Other Architecture Artifacts

The Product Lexicon serves as the shared semantic foundation upon which all other architectural models are built.

**Product Constitution** defines the principles and constraints that guide the platform. The Lexicon provides the canonical vocabulary through which these principles are expressed.

**Educational Concept Model** uses Lexicon concepts as the nodes in its behavioral and causal models. The Lexicon provides the semantic anchors while the ECM defines how they interact.

**Learner Cognitive Model** maps cognitive states and processes to Lexicon concepts. The Lexicon provides the what, while the Cognitive Model defines the how of cognition.

**Instructional Design Model** organizes educational content around Lexicon concepts. The Lexicon provides the semantic structure that guides instructional design.

**Assessment Model** bases assessments on Lexicon concepts. The Lexicon provides the semantic foundation while the Assessment Model defines how to evaluate mastery of those concepts.

**Platform Architecture** implements Lexicon concepts as platform components. The Lexicon provides the what, while the Platform Architecture defines the how of implementation.

### 3.5. Evolution and Stability

While the Product Lexicon provides semantic stability, it also evolves to support changing needs.

**Stable Core**: Core concepts that define the educational domain shall remain stable across versions. Changes to the core shall follow strict governance procedures and require broad consensus.

**Evolving Facades**: Higher-level classification categories and metadata may evolve more frequently to adapt to new research or pedagogical approaches. These changes shall not affect the stability of the core concepts.

**Versioned Evolution**: All changes to the Product Lexicon shall be versioned, documented, and accompanied by migration guidance for downstream consumers.

# 4. Lexicon Governance

### Governance Philosophy

### Governance Authority

### Review Process

### Approval Process

### Change Management

### Versioning

# 5. Canonical Semantic Model

This is the heart of the document.

### 5.1 Purpose

### 5.2 Scope

### 5.3 Architectural Role

### 5.4 Core Components

- Concept Catalog (Canonical Nodes)
- Relationship Catalog (Canonical Edges)

### 5.5 Semantic Layers

- Identity Layer
- Semantic Layer
- Governance Layer

### 5.6 Canonical Semantic Graph

### 5.7 Relationship to Other Architecture Artifacts

# 6. Identity Standards

This governs identity across the semantic model.

### 6.1 Concept Identity

- Canonical ID
- Canonical Name
- Aliases
- Deprecated Names

### 6.2 Relationship Identity

- Canonical Identifier
- Display Name

### 6.3 Identifier Standards

- Format
- Namespace
- Reserved Prefixes
- Immutability

### 6.4 Naming Standards

- Canonical Names
- Canonical Identifiers
- Case
- Singular vs Plural
- Acronyms
- Abbreviations
- Reserved Words

### 6.5 Alias Standards

### 6.6 Identity Governance

# 7. Semantic Taxonomy

This is a new section that I think is extremely valuable.

It classifies the semantic universe.

### 7.1 Concept Categories

Examples

- Product
- Educational
- Cognitive
- Instructional
- Assessment
- Platform
- Architectural

### 7.2 Relationship Families

Examples

- Identity
- Hierarchy
- Composition
Association
- Dependency
- Behavioral

These are controlled vocabularies.

# 8. Canonical Semantic Schema

This section defines the schemas before we populate the catalogs.

### 8.1 Concept Schema (Node Template)

**Identity**

- Canonical ID
- Canonical Name
**Semantic Profile**
- Definition
- Purpose
- Scope
- Category
- Aliases
- Deprecated Names
- Notes
**Governance Metadata**
- Version
- Status
- Owner
- Review Status
- First Introduced
- Last Modified

### 8.2 Relationship Schema (Edge Template)

**Identity**

- Canonical Identifier
- Display Name
**Semantic Profile**
- Relationship Family
- Definition
- Purpose
- Scope
- Directionality
- Inverse Relationship
- Symmetric
- Transitive
**Usage Rules**
- Allowed Artifacts
- Allowed Source Types
- Allowed Target Types
- Constraints
- Examples
**Governance Metadata**
- Version
- Status
- Owner
- Review Status
- First Introduced
- Last Modified

# 9. Domain Hierarchies

### 9.1 Product Hierarchy

### 9.2 Educational Hierarchy

### 9.3 Cognitive Hierarchy

### 9.4 Instructional Hierarchy

### 9.5 Platform Hierarchy

# 10. Concept Catalog (Canonical Nodes)

This is the actual catalog.

Every concept follows the schema defined in Section 8.

No new rules here.

Just governed concepts.

# 11. Relationship Catalog (Canonical Edges)

Likewise.

Every relationship follows the schema defined in Section 8.

No new rules.

Just governed relationships.

# 12. Modeling Rules

Examples

- Every Concept shall have exactly one canonical definition.
- Every Relationship shall use a Relationship Catalog entry.
- Behavioral models instantiate Relationships but never redefine them.
- Every architectural model is a governed semantic view over the Canonical Semantic Model.
- Nodes never define Edges.
- Edges never redefine Nodes.
- No architectural artifact may introduce independent semantic representations.

# 13. Governance Process

Operational lifecycle.

Examples

Concept Proposal

↓

Review

↓

Approval

↓

Publication

↓

Versioning

↓

Deprecation

↓

Retirement

Same for Relationships.

# 14. Future Evolution

Topics

- Semantic Versioning
- Knowledge Preservation
- Backward Compatibility
- Repository Evolution
- Long-term Governance
