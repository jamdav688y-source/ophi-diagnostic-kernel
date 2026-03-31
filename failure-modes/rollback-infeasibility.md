# Failure Mode: Rollback Infeasibility

## Definition

A system or change cannot be reversed within acceptable cost, time, or authority limits.

## Detection Signals

- recovery plans exist only on paper
- rollback requires broad coordination not available in real time
- restoration time is unknown or unacceptable
- deployment proceeds without recovery rehearsal

## Why It Matters

Optimization without realistic rollback turns uncertainty into irreversible downside.

## Risk Profile

Default band: Strategic  
Elevates to Systemic when:
- the change affects core operations
- recovery depends on unavailable experts
- delayed rollback amplifies damage rapidly

## Propagation Path

Irreversible deployment weakens decision quality, because the system becomes less willing or able to correct visible failure.

## Primary Intervention Pattern

- rollback path design
- escalation insertion

## Containment Logic

Require rollback ownership, tested recovery steps, known latency bounds, and escalation if rollback realism is weak.
