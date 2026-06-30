# AGENTS.md

## Purpose

This document explains how AI assistants should interact with the CoproOS Knowledge Repository.

Its objective is to ensure that every AI agent works consistently, respects the repository hierarchy and avoids creating conflicting knowledge.

---

# Core Principles

Every AI assistant should:

- preserve institutional memory;
- minimize knowledge duplication;
- respect canonical documents;
- explain reasoning;
- prefer evolution over expansion.

The objective is not to generate content.

The objective is to improve the repository without degrading its consistency.

---

# Repository Hierarchy

Knowledge authority follows this order:

1. Vision
2. Foundation
3. Product
4. Domain Model
5. Business
6. Architecture
7. Decisions (ADR)

When conflicts exist, higher layers always take precedence.

---

# Canonical Sources

## Vision

Defines the long-term direction.

---

## Foundation

Defines principles, terminology and governance.

---

## Product

Defines customer value.

---

## Domain Model

Defines business reality.

---

## Business

Defines market strategy.

---

## Architecture

Defines technical realization.

---

## ADR

Defines historical decisions.

---

# AI Workflow

Before proposing any modification:

1. Read MASTER_CONTEXT.md.
2. Read the relevant canonical documents.
3. Check existing ADRs.
4. Reuse existing concepts whenever possible.
5. Modify existing documents before creating new ones.

---

# Repository Rules

Always:

- Capture knowledge once.
- Prefer references over duplication.
- Keep documents implementation-independent.
- Preserve terminology.
- Preserve traceability.
- Preserve simplicity.

Never:

- invent business concepts;
- duplicate canonical knowledge;
- introduce competing definitions;
- bypass the Domain Model;
- contradict an accepted ADR.

---

# Creating New Documents

Creating a new document is the exception.

Before creating one, ask:

- Can an existing document be improved?
- Is the new document truly independent?
- Will it remain useful in two years?
- Does it reduce complexity?

If the answer is no, update an existing document instead.

---

# Decision Making

Significant architectural or business decisions should be recorded as ADRs.

AI assistants should recommend ADRs whenever:

- repository structure changes;
- Core Business Concepts change;
- governance rules change;
- architectural direction changes.

---

# Quality Checklist

Before completing any task, verify:

- No duplicated knowledge.
- No broken links.
- No terminology drift.
- No contradiction with Vision.
- No contradiction with Foundation.
- No contradiction with ADRs.

If uncertainty exists, ask for clarification rather than inventing information.

---

# Final Objective

The Knowledge Repository is the institutional memory of CoproOS.

Every contribution should leave the repository more coherent, more traceable and easier for both humans and AI to understand than before.
