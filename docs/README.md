# SigmaOS-power-profiles-daemon — Documentation

## Purpose

SigmaOS power-profiles-daemon component inspired by Linux Mint / Omarchy / Arch Linux.

## Architecture

- `src/lib.rs` — public API (service archetype)
- `tests/` — integration tests
- Mechanism here; policy lives in configuration.

## Principles applied

Abstraction, loose coupling, high cohesion, KISS, DRY, secure defaults,
fail-fast, defensive programming, deterministic testing.
