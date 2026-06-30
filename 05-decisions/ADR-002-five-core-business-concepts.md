# ADR-002 — Five Core Business Concepts

## Status

Accepted

---

## Date

2026-06-30

---

## Context

One of the earliest architectural decisions for CoproOS was determining how to represent the business reality of a condominium.

Many possible concepts were considered, including:

- Decisions
- Documents
- Projects
- Meetings
- Contracts
- Budgets
- Tasks
- Knowledge
- Evidence

The objective was not to model every real-world object independently.

Instead, the objective was to create a stable conceptual model capable of representing the entire business domain while remaining simple enough for humans and AI to reason about consistently.

---

## Decision

The CoproOS Domain Model is based on five Core Business Concepts.

1. Actors
2. Assets
3. Commitments
4. Activities
5. Evidence & Knowledge

Every important business concept should naturally belong to one of these five concepts.

Additional concepts should only become Core Business Concepts if they cannot reasonably be represented within the existing model.

---

## Rationale

This decision intentionally favors simplicity over exhaustive modelling.

The five concepts are broad enough to represent the complete condominium governance domain while remaining understandable by non-technical users.

They also provide stable abstractions that are unlikely to change as the product evolves.

The goal is not to minimise the number of concepts at any cost.

The goal is to minimise unnecessary conceptual complexity.

---

## Consequences

### Positive

- Shared business language.
- Simpler product discussions.
- Stable long-term architecture.
- Easier AI reasoning.
- Easier onboarding.
- Reduced modelling drift.

### Trade-offs

- Some business concepts are represented as specializations rather than independent Core Concepts.
- Concept boundaries must be documented carefully.
- Future evolution requires discipline before introducing new Core Concepts.

---

## Alternatives Considered

### Larger Domain Model

Rejected.

More concepts increase cognitive load and make the repository harder to maintain.

---

### Smaller Domain Model

Rejected.

Reducing the model further would merge concepts with fundamentally different business responsibilities.

---

### Continuous Concept Creation

Rejected.

Creating new Core Concepts whenever new requirements appear leads to conceptual fragmentation and weakens institutional memory.

---

## Decision Criteria

A new Core Business Concept should only be introduced if all of the following are true:

- it represents a genuinely different business reality;
- it cannot naturally be represented by an existing Core Concept;
- introducing it reduces overall complexity rather than increasing it;
- it provides long-term value to the Domain Model.

Otherwise, the existing concepts should be enriched instead.

---

## Related Documents

- 02-domain-model/README.md
- 02-domain-model/domain-overview.md
- 02-domain-model/entities.md
- 02-domain-model/relationships.md
- 02-domain-model/lifecycle.md

---

## Review History

Initial decision recorded on 2026-06-30.

This ADR supersedes the earlier exploratory six-concept model and establishes the five Core Business Concepts as the canonical business model for CoproOS.
