# Intervention Pattern: Rollback Path Design

## Use When

- reversibility is weak
- recovery latency is unknown
- deployment risk is material
- restoration depends on untested assumptions

## What It Changes

Defines:
- rollback ownership
- rollback criteria
- rollback steps
- rollback latency bounds
- recovery validation checks

## What It Fixes

- rollback infeasibility
- false confidence in deployment readiness
- delayed recovery under stress

## Costs Introduced

- more pre-deployment work
- slower optimization cycles
- rehearsal overhead

## New Risks Introduced

- false assurance if rollback plans are never tested

## Reversibility Profile

This pattern exists to improve reversibility.

## Escalation Requirement

Required when no credible rollback path can be demonstrated for a strategic or systemic change.
