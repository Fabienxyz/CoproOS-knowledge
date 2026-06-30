# Product Modules

## Purpose

This document defines the major functional building blocks of CoproOS.

Modules organize the product into coherent business capabilities.

They provide a stable structure for product evolution while remaining independent from implementation details.

Modules are not user interfaces, technical components or database boundaries.

---

# Design Principles

Each module should:

- deliver one or more Strategic Pillars;
- own a coherent business capability;
- remain understandable by non-technical users;
- evolve independently whenever possible;
- avoid overlapping responsibilities.

Modules should remain stable over time even as individual features evolve.

---

# Module Overview

## M-01 — Knowledge

### Purpose

Preserve, organize and exploit the institutional memory of the condominium.

### Supports Strategic Pillars

- SP-01 — Never Lose Your Building's Memory
- SP-04 — Make Better Decisions
- SP-05 — Find Answers Instantly
- SP-10 — Ensure Conseil Syndical Continuity

---

## M-02 — Governance

### Purpose

Support the day-to-day governance of the Conseil Syndical, including meetings, commitments and oversight of the Syndic.

### Supports Strategic Pillars

- SP-02 — Stay in Control of Your Syndic
- SP-04 — Make Better Decisions
- SP-06 — Run Better Conseil Syndical Meetings
- SP-10 — Ensure Conseil Syndical Continuity

---

## M-03 — Operations

### Purpose

Manage everything that evolves over time, including projects, maintenance, incidents, follow-up actions and operational activities.

### Supports Strategic Pillars

- SP-02 — Stay in Control of Your Syndic
- SP-03 — Always Know What Comes Next
- SP-07 — Save Time Every Week

---

## M-04 — Assets

### Purpose

Maintain a structured understanding of the condominium's physical assets, contracts, suppliers and long-term resources.

### Supports Strategic Pillars

- SP-01 — Never Lose Your Building's Memory
- SP-08 — Master Suppliers and Contracts

---

## M-05 — Communication

### Purpose

Facilitate clear, transparent and trusted communication between the Conseil Syndical and co-owners.

### Supports Strategic Pillars

- SP-07 — Save Time Every Week
- SP-09 — Keep Everyone Better Informed

---

## M-06 — Platform

### Purpose

Provide the cross-cutting capabilities required by every module, including artificial intelligence, authentication, notifications, integrations, configuration and security.

Platform capabilities are shared across the entire product and should never become standalone business modules.

### Supports Strategic Pillars

All Strategic Pillars.

---

# Module Relationships

Modules collaborate to deliver customer value.

No module should duplicate the responsibility of another module.

Cross-cutting capabilities belong to the Platform.

Business capabilities belong to business modules.

---

# Governance

New features should always be assigned to an existing module whenever possible.

New modules should be introduced only when an entirely new business capability emerges.

The objective is to keep the product simple, coherent and easy to understand.
