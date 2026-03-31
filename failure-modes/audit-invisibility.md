# Failure Mode: Audit Invisibility

## Definition

Material decisions, actions, or changes cannot be reliably reconstructed after the fact.

## Detection Signals

- missing decision rationale
- undocumented overrides
- unclear approval pathways
- incomplete event logs
- confidence without traceability

## Why It Matters

A system that cannot reconstruct decisions cannot reliably govern them.

## Risk Profile

Default band: Strategic  
Elevates to Systemic when:
- decisions affect safety, finance, or compliance
- hidden actions can compound before discovery
- trust depends on evidence of control

## Propagation Path

Missing records weaken accountability, which lowers correction quality, which increases recurrence and reduces trust.

## Primary Intervention Pattern

- observability upgrade
- constraint hardening

## Containment Logic

Require decision logging, approval lineage, and assumption traceability for consequential actions.
