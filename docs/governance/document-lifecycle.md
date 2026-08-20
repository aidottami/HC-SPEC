---
id: GOV-0001
title: Document Lifecycle
status: draft
visibility: public
ip_class: open-spec
knowledge_type: governance
version: 0.1
created: 2026-08-20
updated: 2026-08-20
---

# Document Lifecycle

## Purpose

Define how HC-SPEC documents move from an initial proposal to canonical, superseded, deprecated, or rejected states.

## Lifecycle

```text
Draft
  ↓
Proposed
  ↓
Under Review
  ↓
Accepted
  ↓
Canonical
  ├──→ Superseded
  └──→ Deprecated

Rejected is a terminal state for proposals that are not adopted.
```

## Rules

- A document MUST declare its lifecycle state in front matter.
- `Draft` content is exploratory and MUST NOT be treated as normative.
- `Proposed` content is ready for structured review.
- `Under Review` content is actively being evaluated.
- `Accepted` means the proposal has been approved but may still require integration into canonical documents.
- `Canonical` content represents the current normative HC-SPEC position.
- `Superseded` content MUST reference the document that replaces it.
- `Deprecated` content remains historically valid but SHOULD NOT guide new implementations.
- `Rejected` proposals remain versioned to preserve decision provenance.

## Principle

The documentation lifecycle mirrors the epistemic model of the Hub Cognitivo: knowledge has state, provenance, history, and explicit promotion rules.
