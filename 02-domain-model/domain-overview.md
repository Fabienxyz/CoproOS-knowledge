# Domain Overview

## Purpose

This document provides a high-level understanding of the business domain represented by CoproOS.

It explains how the core business concepts interact independently from any technical implementation.

Its objective is to provide a shared mental model of the condominium domain for both humans and AI.

---

# The Domain in One Sentence

A condominium is managed by people who make commitments, execute activities, preserve evidence and knowledge, and continuously improve the management of shared assets.

---

# The Five Core Concepts

## Actors

The people and organizations interacting with the condominium.

Actors create commitments, perform activities, produce evidence and use knowledge to make better decisions.

Examples include:

- President of the Conseil Syndical
- Member of the Conseil Syndical
- Syndic
- Co-owner
- Contractor
- Supplier
- Expert
- Public Authority

---

## Assets

Everything the condominium owns, manages or is responsible for.

Examples include:

- Buildings
- Equipment
- Contracts
- Budgets
- Shared facilities
- Technical infrastructure

Assets evolve over time through commitments and activities.

---

## Commitments

A commitment represents something that has been decided, promised, requested or agreed.

Commitments are the operational heart of CoproOS.

Every important action in the condominium ultimately exists because someone committed to making it happen.

Examples include:

- A General Assembly resolution
- A decision by the Conseil Syndical
- A commitment made by the Syndic
- A contractor's obligation
- A regulatory deadline
- A follow-up action

---

## Activities

Activities represent the work performed to fulfill commitments.

Activities happen over time.

They may involve multiple actors, assets and pieces of evidence.

Examples include:

- Renovation work
- Maintenance
- Insurance claims
- Meetings
- Site visits
- Follow-up actions

---

## Evidence & Knowledge

Evidence represents everything that justifies, explains or documents reality.

Knowledge is the trusted operational understanding built from that evidence over time.

Examples include:

- Contracts
- Meeting minutes
- Emails
- Technical reports
- Photos
- Invoices
- Historical context
- Lessons learned

Evidence supports commitments.

Knowledge improves future commitments.

---

# Business Flow

```text
Actors

    ↓ create

Commitments

    ↓ executed through

Activities

    ↓ produce

Evidence & Knowledge

    ↓ improve the management of

Assets

    ↓ provide context for

Actors
```

The cycle continuously repeats throughout the life of the condominium.

Each cycle enriches the institutional memory and improves future governance.

---

# Relationship with the Product

Every Strategic Pillar should be expressible through one or more of these five Core Concepts.

No new Core Concept should be introduced unless it represents a genuinely new aspect of the business domain.

---

# Governance

Before introducing a new business concept, always ask:

> Can it naturally be represented using Actors, Assets, Commitments, Activities, or Evidence & Knowledge?

If the answer is yes, prefer enriching the existing model rather than creating a new Core Concept.

The objective is to keep the Domain Model simple, expressive and stable over time.
