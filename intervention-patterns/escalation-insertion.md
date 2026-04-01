# Intervention Pattern: Escalation Insertion

## Use When

- failures can spread before review
- assumptions are unstable
- risk is increasing faster than local correction can contain
- local teams lack authority to halt or redirect

## What It Changes

Adds:
- trigger conditions
- pause points
- review authority
- mandatory routing under defined thresholds

## What It Fixes

- silent propagation
- delayed review
- unbounded continuation under uncertainty

## Costs Introduced

- interruption overhead
- increased review load
- potential decision friction

## New Risks Introduced

- escalation fatigue
- procedural overreach if thresholds are too sensitive

## Reversibility Profile

High, but trigger tuning may require iteration.

## Escalation Requirement

This pattern is itself an escalation control and should be reviewed when it governs strategic or systemic risk.
