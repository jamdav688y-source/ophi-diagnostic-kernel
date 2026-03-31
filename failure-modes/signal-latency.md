# Failure Mode: Signal Latency

## Definition

The system receives or responds to meaningful changes too slowly to maintain alignment with reality.

## Detection Signals

- declining performance despite reporting confidence
- corrective action arrives after visible damage
- local teams sense issues before central response changes
- market, operational, or security signals are acknowledged late

## Why It Matters

When signal latency exceeds decision cycle tolerance, systems compound error faster than they can correct it.

## Risk Profile

Default band: Operational  
Elevates to Strategic or Systemic when:
- correction cost rises nonlinearly
- delayed action affects multiple dependent systems
- reversibility degrades with time

## Propagation Path

Delay in signal ingestion causes stale decisions, which increase misalignment, which raises correction cost and lowers confidence.

## Primary Intervention Pattern

- observability upgrade
- escalation insertion
- rollback path design

## Containment Logic

Reduce sensing and response latency. Introduce thresholds that force review before error compounds.
