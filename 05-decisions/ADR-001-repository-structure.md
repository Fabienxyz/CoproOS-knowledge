# ADR-001 — Knowledge Repository Structure

## Status

Accepted

---

## Date

2026-06-30

---

## Context

CoproOS is intended to become a long-lived AI-native product.

The Knowledge Repository must remain understandable by both humans and AI throughout the lifetime of the project.

As the product grows, strategy, product, business, architecture and implementation will evolve at different speeds.

A flat documentation structure would quickly become difficult to navigate, difficult to maintain and prone to duplication.

The repository therefore requires a stable structure that separates concerns while preserving traceability.

---

## Decision

The Knowledge Repository is organized into six progressive layers.

1. Foundation
2. Product
3. Domain Model
4. Business
5. Architecture
6. Decisions

Each layer depends only on the layers above it.

Knowledge flows from strategic intent toward implementation.

The Decisions layer records the major choices made during the evolution of the repository and the product.

---

## Rationale

This structure provides:

- a single direction of dependency;
- clear ownership of knowledge;
- minimal duplication;
- stable navigation;
- AI-friendly reasoning;
- long-term maintainability.

It also makes it easier to understand where new knowledge belongs.

---

## Consequences

### Positive

- Clear separation of concerns.
- Better traceability.
- Easier onboarding.
- Reduced documentation drift.
- Better support for AI-assisted development.
- Stable repository growth.

### Trade-offs

- More files to maintain.
- Strong repository governance is required.
- Contributors must understand the layer responsibilities.

---

## Alternatives Considered

### Flat documentation

Rejected.

As the repository grows, authoritative knowledge becomes increasingly difficult to identify.

---

### Knowledge organized by feature

Rejected.

Features evolve much faster than business concepts and create duplicated knowledge.

---

### Knowledge organized by technology

Rejected.

Technology changes.

Business knowledge should remain stable.

---

## Related Documents

- 00-foundation/vision.md
- 00-foundation/design-principles.md
- MASTER_CONTEXT.md

---

## Review History

Initial decision recorded on 2026-06-30.
