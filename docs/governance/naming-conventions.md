# Naming Conventions

Status: Draft

## Purpose

Define stable naming rules for HC-SPEC documents and directories.

## Rules

- Directories use lowercase kebab-case.
- General Markdown documents use lowercase kebab-case filenames.
- RFC files use `RFC-NNNN-short-title.md`.
- ADR files use `ADR-NNNN-short-title.md`.
- Identifiers are immutable once published.
- A renamed concept should preserve redirects or explicit supersession references where practical.
- Acronyms such as HC, MCP, KEE and EVC may remain uppercase in document titles, while filenames remain lowercase.

## Examples

```text
rfc/RFC-0001-core-principles.md
adr/ADR-0001-kafka-event-backbone.md
architecture/knowledge-evolution-engine.md
ontology/hc-meta-ontology.md
```
