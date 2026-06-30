# Design Rules

## Purpose

This document defines the operational rules derived from the Design Principles.

While Design Principles describe *what* the product should achieve and *why*, Design Rules describe *how* those principles are consistently applied throughout the product.

Design Rules are more concrete than Design Principles but remain independent from technical implementation.

---

# Relationship with Design Principles

Every Design Rule must derive from one or more Design Principles.

```text
Vision
    ↓
Design Principles
    ↓
Design Rules
    ↓
Domain Model
    ↓
Features
    ↓
Architecture
    ↓
Source Code
```

A Design Rule must never contradict a Design Principle.

---

# Rule Format

Every Design Rule follows the same structure.

## Identifier

A unique identifier.

Example:

```
DR-001
```

---

## Title

A short descriptive name.

---

## Purpose

Explain why the rule exists.

---

## Rule

Describe the rule itself.

A Design Rule should always be:

- explicit;
- testable;
- implementation-independent;
- unambiguous.

---

## Rationale

Explain which Design Principle(s) motivated the rule.

---

## Examples

Whenever appropriate, provide examples of compliant and non-compliant behavior.

---

# Rule Categories

Design Rules generally belong to one of the following categories.

## Knowledge

Rules governing how knowledge is created, validated, linked and reused.

---

## User Experience

Rules ensuring consistency, clarity and usability.

---

## Artificial Intelligence

Rules governing AI behavior, confidence, explainability and user interaction.

---

## Governance

Rules governing ownership, validation, approvals and responsibilities.

---

## Data Integrity

Rules governing consistency, traceability, versioning and historical preservation.

---

# Design Rule Lifecycle

Every Design Rule follows the same lifecycle.

```text
Draft

↓

Review

↓

Approved

↓

Applied

↓

Deprecated (optional)
```

Only approved Design Rules should influence product decisions.

---

# Governance

New Design Rules should only be created when:

- a Design Principle requires a concrete interpretation;
- the same design decision is repeated multiple times;
- consistency across the product would otherwise become difficult.

Design Rules should remain stable over time.

Product-specific implementation decisions should not become Design Rules.

---

# Quality Criteria

A good Design Rule should be:

- derived from at least one Design Principle;
- understandable in less than two minutes;
- objectively verifiable;
- reusable throughout the product;
- independent of any specific technology.

If a rule cannot satisfy these criteria, it should be reconsidered.

---

# Ownership

Design Rules are human-owned.

AI may propose new rules or improvements.

Only reviewed and validated rules become part of the official Knowledge Repository.
