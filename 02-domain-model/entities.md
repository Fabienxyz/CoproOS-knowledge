# Core Business Concepts

## Purpose

This document defines the five fundamental business concepts that make up the CoproOS Domain Model.

Every feature, workflow and business process should ultimately be expressible through these concepts.

They describe the business, not the software.

---

# Actors

## Purpose

Represent every person or organization interacting with the condominium.

## Owns

Responsibilities, roles and commitments.

## Examples

- President of the Conseil Syndical
- Member of the Conseil Syndical
- Syndic
- Co-owner
- Contractor
- Supplier
- Expert
- Public Authority

## Does NOT include

- Buildings
- Contracts
- Activities
- Evidence

---

# Assets

## Purpose

Represent everything the condominium owns, manages or is responsible for.

## Owns

State, characteristics and lifecycle.

## Examples

- Buildings
- Roof
- Elevator
- Boiler
- Shared facilities
- Budgets
- Contracts

## Does NOT include

- People
- Commitments
- Activities

---

# Commitments

## Purpose

Represent everything that has been decided, promised, requested or agreed.

Commitments are the operational heart of CoproOS.

## Owns

Objectives, responsibilities, deadlines and expected outcomes.

## Examples

- Conseil Syndical decision
- General Assembly resolution
- Syndic commitment
- Contractor obligation
- Regulatory deadline
- Action item

## Does NOT include

- Execution work
- Evidence
- Physical assets

---

# Activities

## Purpose

Represent the execution of work over time.

Activities exist to fulfil commitments.

## Owns

Progress, execution history and operational events.

## Examples

- Renovation
- Maintenance
- Site visit
- Meeting
- Insurance claim
- Inspection

## Does NOT include

- Commitments
- Evidence
- Assets

---

# Evidence & Knowledge

## Purpose

Represent everything that explains, proves or preserves understanding of the condominium.

Evidence records reality.

Knowledge makes reality understandable.

## Owns

Business evidence, historical context and institutional memory.

## Examples

- Meeting minutes
- Emails
- Contracts
- Photos
- Reports
- Invoices
- Historical knowledge
- Lessons learned

## Does NOT include

- Work execution
- Responsibilities
- Physical assets

---

# Governance

Every new business concept should naturally belong to one of these five Core Business Concepts.

If it does not, the Domain Model should be challenged before introducing a sixth concept.
