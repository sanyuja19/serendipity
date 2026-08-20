Status: Draft for implementation
Version: 1.0.0-draft
Authority: Canonical domain vocabulary for SERENDIPITY
Depends on: SPEC-000, SPEC-002, SPEC-003, SPEC-004
Upstream of: SPEC-001, data models, APIs, Knowledge Fabric, AI workflows, frontend implementation

1. Purpose

This document defines the canonical language used by SERENDIPITY to represent scientific knowledge, research activity, evidence, discoveries, and AI-assisted reasoning.

SERENDIPITY is a Research Intelligence Operating System. Its central promise is to organize scientific knowledge into interconnected objects so researchers can move from source material and evidence to relationships, discoveries, hypotheses, and validated research directions.

This specification resolves terminology distributed across the product blueprint, design system, and UI/UX blueprint. No implementation may introduce a new meaning for a canonical term without an explicit architectural decision.

2. Knowledge Object

A Knowledge Object is the canonical conceptual abstraction for a meaningful unit of research information represented, referenced, connected, or reasoned over by SERENDIPITY.

Knowledge Object is a domain abstraction, not necessarily a single physical database table.

Concrete Knowledge Object types include:

Research Asset

Document

Evidence

Concept

Entity

Relationship

Discovery

Hypothesis

Research Question

Operational objects such as Research Mission, Conversation, Notebook Entry, and AI Analysis participate in the research system but are not automatically treated as scientific knowledge merely because they contain knowledge-related content.

Knowledge Object invariants

A concrete Knowledge Object SHOULD have:

stable identifier

object type

workspace ownership or explicit global scope

creation timestamp

update timestamp

lifecycle status where applicable

provenance metadata where applicable

source attribution where applicable

version information where mutable

human/AI authorship classification where applicable

A Knowledge Object MUST NOT silently cross workspace boundaries.

3. Research Asset

A Research Asset is source/domain material brought into SERENDIPITY for research use.

Examples include scientific papers, patents, datasets, and technical reports.

Research Assets remain distinct from Knowledge Fabric entities.

A Research Asset may contain title, authors, publication, year, DOI, source, abstract, keywords, research areas, tags, processing status, and analysis status.

Typical lifecycle:

Uploaded → Processing → Processed → Analyzed

Exceptional states include Processing Failed and Archived.

Archiving does not delete associated discoveries or notebook entries.

4. Document

A Document is the processable textual or structured representation associated with a Research Asset.

A Research Asset represents the source/domain object. A Document represents material extracted, normalized, or made available for processing.

A single Research Asset MAY produce one or more document representations.

5. Evidence

Evidence is a first-class object representing provenance or support for a claim, relationship, discovery, analysis result, or other research assertion.

Evidence SHOULD preserve, where available:

source Research Asset

source Document

page

section

original excerpt

source identifier

location information

creation timestamp

extraction/derivation method

authoring source

confidence or relevance metadata where applicable

Evidence is not itself a claim. A Discovery may be supported by multiple Evidence objects. A Relationship may have one or more supporting Evidence objects.

Provenance is the trace describing where an object, assertion, extraction, transformation, or AI result originated. Provenance MUST remain traceable back to the original Research Asset and Document whenever source material exists.

6. Concept

A Concept is an abstract scientific idea, method, theory, technique, domain concept, or other non-specific scientific notion.

Examples include Graph Neural Network, CRISPR, Molecular Representation Learning, and Federated Learning.

Concept is distinct from Entity and remains a first-class domain object.

7. Entity

An Entity is a concrete named object represented in scientific material.

Examples include researchers, institutions, algorithms, datasets, drugs, organizations, and equipment.

An Entity may participate in multiple typed Relationships and may be connected to Concepts and Research Assets.

8. Relationship

A Relationship is a typed, directed or otherwise explicitly characterized connection between Knowledge Objects.

Examples:

Cites

Uses

Improves

Depends On

Contradicts

Supports

Influences

Relationship semantics MUST be explicit enough that retrieval, visualization, reasoning, and validation can distinguish one relationship type from another.

Relationships derived from research material SHOULD have supporting Evidence. AI-inferred relationships MUST be distinguishable from directly observed source relationships.

9. Knowledge Fabric

The Knowledge Fabric is the connected representation of research knowledge and its relationships.

It is both:

a backend capability for extraction, graph construction, search, and retrieval; and

a user-facing research experience for exploring connected knowledge.

The Knowledge Fabric SHOULD represent Concepts, Entities, Research Assets and relevant references, Evidence, Relationships, and Discoveries where appropriate.

Graph retrieval MUST be progressive and contextual. The browser MUST NOT receive or render the entire graph for ordinary exploration.

Storage responsibilities

The existing architecture assigns:

PostgreSQL: users, workspaces, metadata, operational records, reports, and structured application state.

Neo4j: concepts, entities, relationships, citations, and Knowledge Fabric connections.

Vector database: embeddings, chunks, and semantic retrieval representations.

Object storage: uploaded files and exports.

These are architectural responsibilities. Frontend code MUST NOT access these stores directly.

10. Discovery

A Discovery is a candidate higher-level research insight produced from connected knowledge and evidence.

A Discovery may identify a previously unnoticed relationship, cross-domain connection, research opportunity, surprising pattern, or underexplored combination of methods or concepts.

A Discovery SHOULD include:

statement

context

related Knowledge Objects

supporting Evidence

confidence

generation timestamp

provenance

source Research Mission or analysis where applicable

lifecycle status

A Discovery MUST NOT be represented as a verified scientific conclusion merely because an AI system generated it.

11. Discovery Report

A Discovery Report is a presentation or persisted report assembled from one or more Discoveries, their Evidence, and related research context.

Therefore:

Discovery = underlying candidate research insight

Discovery Report = structured presentation of one or more discoveries

A Discovery Report may contain an executive summary, discovery statements, evidence, related concepts/entities, supporting research, confidence, limitations, and suggested next steps.

12. Hypothesis

A Hypothesis is a candidate proposition derived from a Discovery or research question that is suitable for researcher investigation or experimental validation.

A Hypothesis is not automatically a scientific conclusion.

Canonical progression:

Knowledge + Evidence → Discovery → Researcher Investigation → Hypothesis → Validation/Experiment

13. Research Question

A Research Question is the researcher's explicit question or problem framing that establishes the context for investigation.

It may initiate a Research Mission, provide context for a Discovery, guide retrieval, constrain reasoning, or become associated with Notebook work.

Persisted Research Questions SHOULD have stable identity rather than being treated only as transient strings.

14. Research Mission

A Research Mission is a persistent execution context for an AI-assisted research task.

A Mission connects research question, workspace, retrieval, analysis, reasoning, discovery, validation, events, and outputs.

Mission lifecycle

Draft → Configured → Queued → Running → Paused → Completed

Exceptional states:

Partially Completed

Failed

Retrying

Cancelled

State transitions MUST be explicit and observable.

Functional agent roles

The later Mission-oriented architecture is authoritative over earlier linear agent naming.

Canonical functional roles:

Planner

Retrieval

Literature

Knowledge

Reasoning

Discovery

Validation

Implementations may decompose or combine internal workers without changing these domain responsibilities.

15. Mission Event

A Mission Event records meaningful execution progress or state transitions.

It SHOULD contain event type, timestamp, mission identifier, status, agent/worker role where applicable, structured payload, and error information where applicable.

Mission event history supports observability, resilience, and user-visible execution timelines.

16. AI Analysis

AI Analysis represents a structured analysis operation or result produced by AI over research material.

It may include summaries, extracted concepts, extracted entities, extracted relationships, evidence references, analytical observations, model/provider metadata, timestamps, and status.

AI Analysis is an operational research artifact. It does not automatically become authoritative knowledge.

17. Conversation and Research Copilot

A Conversation represents persistent conversational context between a researcher and SERENDIPITY.

The Research Copilot is the conversational research interface. It is not a generic chatbot.

Copilot responses SHOULD be grounded in the active research context and SHOULD expose relevant evidence when making research claims.

A Copilot query MAY invoke a Research Mission when the task requires persistent or multi-step execution, through an explicit application contract.

18. Notebook Entry

A Notebook Entry is researcher-owned research context captured inside a workspace.

It may contain notes, references to Knowledge Objects, Evidence, Discoveries, hypotheses, research questions, and links to Research Assets.

Notebook entries preserve provenance when content is derived from research material.

19. Workspace Memory

Workspace Memory is persistent contextual information used to maintain research continuity within a workspace.

Workspace Memory MUST be isolated from other workspaces unless explicitly shared through an authorized mechanism.

AI retrieval MUST respect workspace boundaries.

20. Processing Job

A Processing Job represents asynchronous work such as document extraction, parsing, chunking, embedding, entity/concept extraction, relationship extraction, graph updates, and report generation.

Heavy work SHOULD be asynchronous. Processing status MUST be observable and failures MUST be represented explicitly.

21. Authorship and Origin

SERENDIPITY distinguishes at minimum:

researcher-authored

source-derived

AI-generated

AI-inferred

system-generated

Origin MUST NOT be hidden when it materially affects interpretation.

AI-generated or inferred content MUST NOT be silently represented as researcher-authored or source-derived content.

22. Confidence

Confidence describes the system's degree of confidence in an inferred or generated assertion.

Confidence is not equivalent to scientific truth.

Where confidence is shown, the UI SHOULD expose supporting Evidence and context so the researcher can evaluate the assertion.

23. Workspace Isolation

Workspace isolation is a hard invariant.

Workspace-specific information SHALL never appear in another workspace unless explicitly shared.

This includes Research Assets, Knowledge Fabric entities, Concepts, Evidence, AI memory, Discoveries, Notebook Entries, Research Missions, Reports, and Conversations.

Every workspace-scoped object MUST have an enforceable workspace boundary.

Isolation must be enforced in backend authorization and data access, not only in the UI.

24. Lifecycle and Versioning

Mutable Knowledge Objects SHOULD support version-aware updates.

A change MUST NOT destroy the provenance of earlier states where historical state matters to scientific interpretation.

Generated discoveries and analyses SHOULD preserve the execution context required to inspect their origin where practical.

25. Canonical Research Intelligence Flow

Research Question
       ↓
Research Mission
       ↓
Research Assets
       ↓
Documents
       ↓
Processing
       ↓
Evidence
       ↓
Concepts + Entities
       ↓
Relationships
       ↓
Knowledge Fabric
       ↓
Reasoning
       ↓
Discovery
       ↓
Researcher Investigation
       ↓
Hypothesis
       ↓
Validation / Experiment
       ↓
Evidence-backed research output

This is a domain model, not a requirement that every interaction execute every step.

26. Canonical Vocabulary

Term

Canonical meaning

Knowledge Object

Abstract domain-level unit of research information

Research Asset

Source/domain research material

Document

Processable representation associated with a Research Asset

Evidence

First-class support/provenance object

Concept

Abstract scientific idea or method

Entity

Concrete named object

Relationship

Typed connection between objects

Knowledge Fabric

Connected knowledge representation and experience

Discovery

Candidate higher-level research insight

Discovery Report

Presentation/structured report of discoveries and evidence

Hypothesis

Candidate proposition for investigation/validation

Research Question

Researcher's explicit investigation framing

Research Mission

Persistent AI-assisted research execution context

Mission Event

Observable Mission execution event

AI Analysis

Structured AI analysis artifact

Conversation

Persistent research conversation context

Notebook Entry

Researcher-owned research note/context

Workspace Memory

Persistent workspace context used for continuity

Processing Job

Asynchronous processing operation

Research Copilot

Conversational research interface

27. Ontology Extension Rules

A new domain object SHOULD NOT be introduced merely because a feature needs a new database table.

Before adding a new canonical object:

determine whether an existing Knowledge Object type already represents it;

determine whether it is an operational object rather than scientific knowledge;

define its relationship to existing objects;

define workspace scope;

define provenance requirements;

define lifecycle;

update this specification;

record an ADR when the change affects architecture or established terminology.

No implementation should silently create a competing vocabulary.

28. Implementation Constraints

Database models MUST reflect canonical domain meanings rather than merely copying UI labels.

API schemas MUST use canonical terminology.

Graph node and relationship types MUST preserve canonical semantics.

Evidence and provenance MUST remain traceable.

Workspace isolation MUST be enforced server-side.

AI-generated assertions MUST remain distinguishable from source-derived evidence.

Discoveries MUST NOT be presented as verified scientific conclusions.

Graph retrieval MUST support progressive/contextual retrieval.

Frontend code MUST NOT directly access PostgreSQL, graph databases, vector stores, object storage, or model providers.

Heavy processing MUST be represented as observable asynchronous jobs where appropriate.

29. Examples

Source to Knowledge Fabric

Research Asset
      ↓
Document
      ↓
Evidence
      ↓
Concept + Entity
      ↓
Relationship
      ↓
Knowledge Fabric

Discovery

Evidence A
+ Evidence B
+ Concept relationship
+ Cross-domain connection
        ↓
Discovery
        ↓
Evidence + Confidence + Related Objects

The Discovery remains a candidate insight requiring researcher evaluation.

30. Authority and Change Control

This document is the canonical source for SERENDIPITY domain vocabulary.

If another specification conflicts with this document:

identify the conflict;

do not silently choose one meaning;

resolve it through an explicit specification update or ADR.

SPEC-001 consumes this vocabulary when defining requirements.

Database models, APIs, Knowledge Fabric schemas, AI workflows, and frontend domain representations MUST derive terminology from this specification.

31. Definition of Done

This specification is implementation-ready when:

canonical terms have definitions;

object boundaries are explicit;

Concept and Entity are distinct;

Evidence is first-class;

Discovery and Discovery Report are distinct;

Discovery → Hypothesis progression is explicit;

Research Mission lifecycle is explicit;

workspace isolation is explicit;

provenance semantics are explicit;

AI-generated and source-derived information are distinguishable;

storage responsibilities are documented;

extension rules are defined;

unresolved contradictions are recorded rather than hidden.

32. Implementation Note

This document intentionally defines the domain contract, not a premature physical database schema.

The next implementation documents should derive:

relational models and migrations,

graph schema,

vector/indexing schema,

API contracts,

event contracts,

AI/agent contracts,

from this language.

The system should be built from the domain model outward, not from database tables inward.