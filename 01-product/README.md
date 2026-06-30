# Product

## Purpose

The Product section defines what CoproOS delivers to its users.

It describes the value created for the Conseil Syndical, the problems being solved, the product philosophy and the functional building blocks that together form the product.

This section answers:

> **What should we build to create meaningful value for our users?**

---

# Scope

The Product section defines:

- the product value proposition;
- the target users;
- the major product modules;
- the product philosophy.

These documents describe the product from a user and business perspective.

They intentionally avoid implementation details.

---

# Out of Scope

This section does **not** contain:

- technical architecture;
- implementation details;
- source code;
- database models;
- APIs;
- infrastructure;
- engineering decisions.

These belong to later sections of the Knowledge Repository.

---

# Guiding Principle

> Every feature must contribute to a clear customer value.

Features exist to support the product's value proposition.

They should never exist simply because they are technically interesting or easy to implement.

---

# Product Philosophy

CoproOS is not built around features.

It is built around customer value.

The product follows a simple hierarchy.

```text
Vision
    ↓
Foundation
    ↓
Product
    ↓
Domain Model
    ↓
Business
    ↓
Architecture
    ↓
Decisions
```

The Product layer defines value and modules. The business reality is defined in [02-domain-model/](../02-domain-model/). Technical realization belongs in [04-architecture/](../04-architecture/).

Every product decision should strengthen one or more Value Proposition pillars.

If a feature does not reinforce a measurable customer value, it should be challenged before implementation.

---

# Documents

| Document | Purpose |
|----------|---------|
| value-proposition.md | Defines why customers buy CoproOS and the value delivered by the product. |
| modules.md | Defines the major functional modules that deliver this value. |
| personas.md | Defines the primary and secondary users of the product. |
| product-philosophy.md | Defines the principles used to make product decisions over time. |

---

# Governance

The Product documentation evolves more frequently than the Foundation.

However, every product decision must remain consistent with:

- the Vision;
- the Design Principles;
- the Design Rules.

The Product section defines **what** the product should become.

The Domain Model defines **what reality** the product represents.

The Architecture section defines **how** it will be built.
