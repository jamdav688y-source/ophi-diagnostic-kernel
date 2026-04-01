# Intervention Pattern: Observability Upgrade

## Use When

- signals arrive too late
- diagnosis depends on anecdote
- decision trails are incomplete
- coordination failures remain invisible until after damage

## What It Changes

Improves visibility into:
- state changes
- decision lineage
- override activity
- recovery performance
- drift indicators

## What It Fixes

- signal latency
- audit invisibility
- hidden divergence
- delayed correction

## Costs Introduced

- instrumentation overhead
- added monitoring complexity
- possible alert fatigue

## New Risks Introduced

- false confidence from noisy data
- monitoring without response discipline

## Reversibility Profile

High, though instrumentation scope may need adjustment.

## Escalation Requirement

Required when improved observability reveals strategic or systemic conditions previously hidden.
