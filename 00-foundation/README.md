# 00 — Foundation

## Purpose

The Foundation is the stable constitutional layer of the CoproOS Knowledge Repository. It defines what the project is, how it should be designed, and the vocabulary shared across all other layers.

Changes here are rare and deliberate. Everything else in the repository derives from this layer.

## What Belongs Here

- Project vision and scope boundaries
- Design Principles that govern product and engineering decisions
- Design Rules derived from those principles
- Shared glossary and terminology

## What Does Not Belong Here

- Business rules, domain models, or feature specifications
- Architecture decisions (see `04-decisions-adr/`)
- Implementation details or source code
- Current priorities, drafts, or work-in-progress

## Guiding Principle

The repository is the source of truth. The Foundation holds the highest-level, most stable knowledge. Lower layers must remain consistent with it; if they conflict, the lower layer is reconsidered before the Foundation is changed.

## Documents

| Document | Role |
|----------|------|
| [vision.md](vision.md) | Why the project exists, the problem it addresses, and what success looks like |
| [design-principles.md](design-principles.md) | Non-negotiable and product design principles; the highest-level technical reference |
| [design-rules.md](design-rules.md) | Concrete rules derived from Design Principles |
| [glossary.md](glossary.md) | Shared definitions and terminology |
