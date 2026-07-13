# Event Bus

## Purpose
The Event Bus provides decoupled publish/subscribe communication across modules.

## Responsibilities
- Queue events.
- Dispatch events during flush.
- Support deterministic replay-ready ordering.
- Prevent direct cross-module coupling.

## Architectural Rules
- Events are queued before dispatch.
- Subscribers are keyed by event type.
- Event routing must not use fragile string matching.
- The Event Bus must support safe unsubscription during publish.

## Related ADRs
- ADR-04
- ADR-07
- ADR-08
- ADR-15
