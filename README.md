# Synthesis REA

**Status, scaffold and design specification.**

Synthesis REA is intended to compare results from multiple REA investigations, identify agreement and contradiction, and propose testable hypotheses. This repository does not yet provide a completed synthesis engine.

## Intended inputs

- Structured investigation records from REA Core.
- Findings with explicit evidence references.
- Known limitations, confidence statements and method metadata.
- Optional independent reviews or replication results.

## Intended outputs

A synthesis record should distinguish supported findings, conflicting findings, connections that remain hypotheses, missing evidence, proposed experiments and limitations introduced by incompatible methods or datasets.

## Core rule

A pattern across multiple reports is not automatically independent confirmation. Preserve source provenance and identify when reports share underlying data, models or assumptions.

## Relationship to other projects

- [REA](https://github.com/DerekWiner/rea) defines the ecosystem and methodology.
- [REA Core](https://github.com/DerekWiner/rea-core) provides the shared record contract.
- REA Orchestrator is intended to route investigation tasks.
- Synthesis REA is intended to compare completed records.

## Current status and next milestone

Cross-investigation comparison, contradiction detection, hypothesis generation and evidence dependency analysis remain to be implemented and evaluated.

Create a deterministic example that compares two hand-authored REA Core records and emits agreement, disagreement, shared-source warnings and unresolved questions. Test against known examples before adding model-generated synthesis.
