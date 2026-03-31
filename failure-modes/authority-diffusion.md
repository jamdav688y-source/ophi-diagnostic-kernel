# Failure Mode: Authority Diffusion

## Definition

Decision responsibility is distributed across actors without clear ownership, intervention rights, or stop authority.

## Detection Signals

- repeated ambiguity over who decides
- delayed intervention during failure
- multiple actors assume others own the issue
- conflicting instructions across layers
- escalation occurs late or not at all

## Why It Matters

Systems with unclear authority fail under pressure because action latency increases exactly when decisive control is needed.

## Risk Profile

Default band: Strategic  
Elevates to Systemic when:
- the system spans multiple teams or domains
- the failure affects safety, governance, or major continuity
- rollback requires authority that is undefined

## Propagation Path

Unclear authority leads to delayed correction, which increases spread, which increases coordination cost, which further delays correction.

## Primary Intervention Pattern

- authority rebinding
- escalation insertion

## Containment Logic

Assign:
- named decision owner
- explicit stop-authority holder
- escalation threshold and recipient
