# Platform Kernel

## Purpose
The Platform Kernel is the singular root orchestrator of MarketPilot.

## Responsibilities
- Boot the platform.
- Host the Capability Registry.
- Host the Event Bus.
- Manage kernel state.
- Enforce lifecycle order.
- Remain free of business logic.

## Architectural Rules
- The Kernel depends only on interfaces.
- Concrete service creation is delegated to the CoreFactory.
- The Kernel is the only Autoload.
- The Kernel must not know trading logic.

## Related ADRs
- ADR-03
- ADR-04
- ADR-08
- ADR-15
