# Repository Rules

These rules are intentionally lightweight so sample planning PRs can demonstrate how an agent should check existing constraints before implementation.

## Engineering Rules

- Prefer incremental changes that keep rollback straightforward.
- Keep domain logic independent from transport, storage, and vendor-specific services.
- Add durable workflows behind explicit feature flags when the user experience or data model changes.
- Do not introduce a new persistence model unless the plan explains migration, observability, and rollback.
- Do not bypass existing audit trails for user-visible or financial state transitions.

## Planning Rules

- Complex work should start with a planning PR before implementation.
- PR bodies should stay concise and skimmable.
- Detailed tradeoffs belong in a documentation file committed with the PR.
- If an existing rule or ADR blocks the cleanest design, call that out directly instead of silently working around it.

