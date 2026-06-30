# Business Relationships

## Purpose

This document defines how the Core Business Concepts relate to one another.

Relationships describe the business reality represented by CoproOS.

They are independent from software implementation.

---

# Design Principles

Relationships should:

- represent real business interactions;
- be easy to understand by non-technical stakeholders;
- remain stable over time;
- avoid unnecessary complexity.

A relationship should describe something that is true in the real world.

---

# Relationship Overview

| ID | Relationship |
|----|--------------|
| R-01 | Actors create Commitments |
| R-02 | Actors perform Activities |
| R-03 | Actors produce Evidence & Knowledge |
| R-04 | Commitments concern Assets |
| R-05 | Commitments are fulfilled through Activities |
| R-06 | Activities involve Assets |
| R-07 | Activities produce Evidence & Knowledge |
| R-08 | Evidence & Knowledge supports Commitments |
| R-09 | Evidence & Knowledge explains Assets |
| R-10 | Evidence & Knowledge improves future Commitments |

---

# Relationship Descriptions

## R-01 — Actors create Commitments

Every commitment originates from one or more actors.

Examples:

- The Conseil Syndical decides to renovate the roof.
- The Syndic commits to requesting quotations.
- A contractor commits to completing work.

---

## R-02 — Actors perform Activities

Activities are always carried out by one or more actors.

---

## R-03 — Actors produce Evidence & Knowledge

Actors create evidence through their work and interactions.

Knowledge grows over time from accumulated evidence.

---

## R-04 — Commitments concern Assets

Every commitment exists for one or more condominium assets.

Examples:

- Elevator
- Roof
- Building
- Budget
- Insurance contract

---

## R-05 — Commitments are fulfilled through Activities

Activities represent the operational execution of commitments.

One commitment may require many activities.

---

## R-06 — Activities involve Assets

Activities modify, inspect, maintain or evaluate assets.

---

## R-07 — Activities produce Evidence & Knowledge

Execution generates documents, reports, photographs, emails, observations and operational knowledge.

---

## R-08 — Evidence & Knowledge supports Commitments

Evidence justifies commitments.

Knowledge improves the quality of future commitments.

---

## R-09 — Evidence & Knowledge explains Assets

Every important asset should become progressively better understood over time.

---

## R-10 — Evidence & Knowledge improves future Commitments

The institutional memory created by CoproOS enables better governance and better future decisions.

This closes the continuous learning cycle.

---

# The Business Cycle

```text
Actors
      │
      ▼
Commitments
      │
      ▼
Activities
      │
      ▼
Evidence & Knowledge
      │
      ▼
Assets
      │
      ▼
Actors
```

This cycle continuously repeats throughout the life of the condominium.

Each cycle enriches the institutional memory and improves governance.

---

# Governance

New relationships should only be introduced when they represent a genuine business interaction.

Whenever possible, enrich existing relationships instead of creating new ones.

The objective is to keep the Domain Model expressive, stable and easy to understand.
