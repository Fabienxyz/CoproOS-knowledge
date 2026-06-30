# Domain Model

## Purpose

The Domain Model defines the business reality represented by CoproOS.

It identifies the fundamental concepts that exist independently of software implementation and provides the common language shared by Product, Architecture and AI.

The Domain Model answers one question:

> **What reality does CoproOS represent?**

---

# Guiding Principle

Model the business before modelling the software.

Technology changes.

The business domain should remain stable.

---

# The Five Core Business Concepts

The CoproOS Domain Model is built around five fundamental concepts.

- **Actors** — Who interacts with the condominium.
- **Assets** — What the condominium owns or manages.
- **Commitments** — What has been decided, promised or agreed.
- **Activities** — How commitments are executed.
- **Evidence & Knowledge** — Why the system knows what it knows.

These concepts form the shared language of CoproOS.

No additional Core Business Concept should be introduced unless it cannot naturally be represented by one of these five.

---

# Domain Documentation

The Domain Model is progressively refined through the following documents.

## domain-overview.md

Provides the high-level business view of the domain.

---

## entities.md

Defines each Core Business Concept.

---

## relationships.md

Describes how the Core Business Concepts interact.

---

## lifecycle.md

Explains how the domain continuously evolves over time.

---

# Relationship With The Repository

The Domain Model translates the Product Vision into business concepts.

It is implementation-independent.

The Architecture layer is responsible for translating these business concepts into software.

---

# Governance

Changes to the Domain Model should be rare.

Every change must preserve:

- simplicity;
- consistency;
- traceability;
- long-term stability.

The Domain Model represents the business, not the implementation.
