# ADR 0002: Portable Core Domain

## Status

Accepted

## Decision

Core domain logic should remain portable across runtime, storage, and vendor choices.

## Consequences

- Business rules should not depend directly on one cloud vendor, queue vendor, or database-specific feature.
- Infrastructure-specific code should live at the edge behind interfaces.
- Exceptions require an explicit migration and exit strategy.

