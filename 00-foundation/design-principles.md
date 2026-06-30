# Purpose

This document defines the stable principles governing the design of CoproOS.

Every Business Rule, Domain Model, Feature, Architecture Decision and Source Code implementation must derive from these principles.

If an implementation conflicts with a Design Principle, the implementation should be reconsidered before changing the principle.

# Principle Hierarchy

## Tier 1 — Non-negotiable Principles

These principles protect trust, integrity and legal reliability.

- DP-001 Reality over Documents
- DP-003 Traceability by Design
- DP-008 Human Ownership
- DP-009 History is Preserved

## Tier 2 — Product Design Principles

- DP-002 Explicit Knowledge
- DP-004 Capture Once
- DP-005 Explainable Recommendations

## Tier 3 — Optimization Principles

- DP-006 Simplicity First
- DP-007 Progressive Knowledge

# Product Design Principles

## DP-001 — Reality over Documents

### Principle

The system models the real world.
Documents are evidence of reality.

### Why

### Consequences

## DP-002 — Explicit Knowledge

### Principle

Clearly distinguish:

- Facts
- Inferences
- Hypotheses

Never present assumptions as facts.

### Why

### Consequences

## DP-003 — Traceability by Design

### Principle

Every important piece of information must be traceable back to its source.

### Why

### Consequences

## DP-004 — Capture Once

### Principle

Information should only be entered once.
The system reuses, links and enriches it.

### Why

### Consequences

## DP-005 — Explainable Recommendations

### Principle

Every recommendation must be explainable.

### Why

### Consequences

## DP-006 — Simplicity First

### Principle

Prefer the simplest solution that satisfies the need.

### Why

### Consequences

## DP-007 — Progressive Knowledge

### Principle

Knowledge grows progressively over time.

### Why

### Consequences

## DP-008 — Human Ownership

### Principle

The system assists.
Humans decide.

### Why

### Consequences

## DP-009 — History is Preserved

### Principle

Significant actions are recorded instead of overwritten.
Corrections extend history.
Historical events are append-only.

### Why

### Consequences

# Engineering Principles

## EP-001 — Solo Build

### Principle

The product must remain buildable by a single developer using AI-assisted development.

### Why

### Consequences

## EP-002 — Explainable Architecture

### Principle

Every architectural decision must be explainable in less than five minutes.

### Why

### Consequences

## EP-003 — Evolution over Rewrite

### Principle

The architecture must evolve incrementally without major rewrites.

### Why

### Consequences

## EP-004 — Simplicity Wins

### Principle

When two solutions provide comparable value, choose the simplest one.

### Why

### Consequences

# Architecture Decision Filter

Use this checklist before committing to an architectural or product decision.

## Product

- Respect Tier 1 principles?
- Respect Product Design Principles?

## Engineering

- Can I build it alone with Cursor?
- Can I explain it in less than five minutes?
- Can I evolve it without rewriting everything?
- Is there a simpler solution?

If any answer is negative, the decision must be challenged before implementation.

# Governance

Design Principles are the highest-level technical reference of the project.

Every Design Rule, Domain Model, Feature, Architecture Decision and Source Code implementation must remain consistent with these principles.

These principles should change only in exceptional circumstances.
