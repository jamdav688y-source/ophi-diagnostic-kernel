# Failure Mode: Distributed Drift

## Definition

Multiple actors or subsystems optimize locally and gradually diverge from shared objectives, constraints, or control logic.

## Detection Signals

- outputs conflict across teams or agents
- reconciliation overhead rises over time
- decision logs show inconsistent assumptions
- policies are interpreted differently across domains

## Why It Matters

Distributed drift produces systemic incoherence without a single obvious point of failure.

## Risk Profile

Default band: Strategic  
Elevates to Systemic when:
- shared systems rely on coordinated behavior
- no common override logic exists
- drift affects safety, trust, or compliance

## Propagation Path

Local optimization increases divergence, divergence increases coordination friction, friction weakens coherence, and the system fragments.

## Primary Intervention Pattern

- constraint hardening
- authority rebinding
- observability upgrade

## Containment Logic

Re-establish shared control logic, shared definitions, and named reconciliation authority.
