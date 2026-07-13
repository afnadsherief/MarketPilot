# Core Factory

## Purpose
The Core Factory constructs core services without coupling callers to concrete implementations.

## Responsibilities
- Create logger instances.
- Create registry instances.
- Create event bus instances.
- Preserve swappable implementations.

## Architectural Rules
- The Platform Kernel must not instantiate concrete core services directly.
- The factory preserves future replacement of implementations.
- The factory supports ADR-15 scalability.

## Related ADRs
- ADR-04
- ADR-15
