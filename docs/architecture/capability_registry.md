# Capability Registry

## Purpose
The Capability Registry stores and resolves platform capabilities through strongly typed identifiers.

## Responsibilities
- Register services.
- Resolve services.
- Detect missing capabilities.
- Support dependency injection for modules.

## Architectural Rules
- Use Script-based identifiers for strong typing.
- Avoid string-based capability names where possible.
- Registry lookups are owned by the Platform Kernel.

## Related ADRs
- ADR-04
- ADR-06
- ADR-08
- ADR-15
