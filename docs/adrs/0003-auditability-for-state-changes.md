# ADR 0003: Auditability for State Changes

## Status

Accepted

## Decision

User-visible state transitions and regulated state transitions must be auditable.

## Consequences

- Plans must identify the source of truth.
- Plans must describe how failed, duplicate, delayed, or replayed operations are detected.
- Plans that add new state transitions must include observability and recovery notes.

