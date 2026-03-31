# Diagnostic Protocol

## Objective

Provide a repeatable method for detecting failure, classifying risk, and mapping diagnosis to intervention.

## Protocol

### Step 1: Define the system boundary
Identify:
- what system is under evaluation
- what lies inside the decision boundary
- what lies outside it
- what interfaces matter

### Step 2: Identify the governing objective
State the system's operative objective in exact language.

Examples:
- preserve uptime under attack
- maintain decision quality under scale
- deploy AI without governance erosion
- restore service within bounded latency

### Step 3: Extract constraints
Identify:
- legal constraints
- ethical constraints
- technical constraints
- operational constraints
- resource constraints
- time constraints

No diagnosis is complete without explicit constraints.

### Step 4: Detect failure signals
Look for signals such as:
- latency growth
- authority ambiguity
- conflicting outputs
- increased override frequency
- audit gaps
- rising recovery cost
- unbounded optimization pressure

### Step 5: Classify the failure type
Map observed conditions to a known failure class.

Examples:
- signal latency
- authority diffusion
- distributed drift
- constraint erosion
- audit invisibility
- rollback infeasibility

### Step 6: Assess risk
Classify risk by:
- impact
- scope
- reversibility
- resource exposure
- ethical/legal exposure
- cascading potential

### Step 7: Map propagation path
Identify how the failure spreads:
- local only
- subsystem chain
- cross-boundary cascade
- systemic degradation

### Step 8: Select intervention pattern
Choose one or more bounded intervention patterns:
- authority rebinding
- escalation insertion
- constraint hardening
- rollback path design
- observability upgrade

### Step 9: Evaluate reversibility
Determine:
- whether the intervention can be rolled back
- the cost of rollback
- expected rollback latency
- who can authorize it

### Step 10: Escalate when required
Escalate when:
- risk is strategic or systemic
- assumptions are materially unstable
- ethical ambiguity exists
- rollback is weak or absent
- intervention requires authority not held

### Step 11: Record diagnostic output
Every diagnosis should include:
- objective
- constraints
- signals
- failure classification
- risk band
- propagation path
- proposed interventions
- assumptions
- tradeoffs
- escalation status
