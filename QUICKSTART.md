# Quickstart

This quickstart is for operators who want to use the OPHI Diagnostic Kernel without reading the full doctrine first.

## Goal

Use the kernel to diagnose a failure boundary and identify a bounded intervention.

## 10-Minute Workflow

### Step 1 — Define the boundary
Write down the system, workflow, discourse, or decision boundary under review.

Questions:
- What system is being examined?
- Where does failure become consequential?
- What cannot be allowed to drift?

### Step 2 — Identify signals
Collect the observable indicators that something is breaking.

Examples:
- late escalation
- authority ambiguity
- rollback impossibility
- coordination delay
- policy drift
- unbounded optimization pressure

### Step 3 — Select a failure mode
Open `/failure-modes` and choose the failure class that best matches the situation.

If no file fits, create a new one from the template in `/templates`.

### Step 4 — Map propagation
Describe how the failure spreads if left untreated.

Questions:
- What gets worse first?
- What crosses boundaries next?
- What becomes expensive or irreversible?

### Step 5 — Choose a bounded intervention
Open `/intervention-patterns` and select the intervention that changes the trajectory without creating uncontrolled side effects.

### Step 6 — Record the diagnostic
Use the template in `/templates/case-study-template.md` or `/templates/diagnostic-template.md` to preserve:
- boundary
- signals
- failure class
- propagation path
- intervention
- audit notes

## Minimum Rule

A kernel artifact is not complete until it answers:
- what is breaking
- why it is breaking this way
- what bounded intervention changes the outcome

## Recommended Starting Files

- `README.md`
- `ARCHITECTURE_OVERVIEW.md`
- `docs/`
- `failure-modes/`
- `intervention-patterns/`
- `templates/case-study-template.md`

## Intended Use Modes

- AI governance review
- operational risk diagnosis
- decision-boundary analysis
- intervention architecture
- public case-study analysis
