# Testing Strategy

## Purpose
Define the test strategy for MarketPilot implementation.

## Principles
- Use GUT for Godot unit tests.
- Keep core logic testable in isolation.
- Prefer deterministic tests.
- Cover registry, event routing, lifecycle, and kernel behavior.

## Required Coverage for Milestone 1
- Registry registration and overwrite behavior.
- Event queueing and flush ordering.
- Safe unsubscribe during publish.
- High-volume publish stress.
- Kernel boot state transitions.

## Related ADRs
- ADR-13
