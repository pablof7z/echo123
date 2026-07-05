# ADR 0001: Boundary-First Planning

## Status

Accepted

## Decision

Plans for complex work must identify the main system boundaries before proposing implementation steps.

## Consequences

- Prefer small adapters over broad shared abstractions.
- Make ownership clear before adding cross-cutting infrastructure.
- Document any boundary changes in the planning PR.

