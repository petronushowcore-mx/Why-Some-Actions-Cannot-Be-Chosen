# Authorization Before Choice

This repository contains the formal paper:

**“Why Some Actions Cannot Be Chosen: Authorization Preceding Optimization in Long-Horizon Systems”**

The work establishes a minimal architectural claim:

> Some actions cannot be explained as the result of choice or optimization.

## What This Is

This repository is an **architectural anchor**, not an implementation.
It exposes a single structural layer: **authorization as a prerequisite for action execution**.

The paper shows that for actions with irreversible consequences, admissibility must be
resolved before any act of comparison, evaluation, or optimization can occur.
As a result, choice is not a sufficient explanatory primitive for action execution.

## What This Is Not

- Not a learning algorithm  
- Not a controller or planner  
- Not a safety or alignment method  
- Not a constrained optimization trick  

No code, simulations, or worked examples are intentionally provided.

## Why This Exists

Many modern agent and control architectures implicitly assume that all actions are admissible
and differ only in expected value. This work shows that this assumption fails in long-horizon
systems with irreversible structural consequences.

The goal is to fix a missing architectural boundary, not to propose a complete system.

## License

- Paper: CC BY 4.0 (see Zenodo DOI)
- Repository: MIT License

This repository establishes prior art and invites discussion, critique, and extension.
Implementation, commercialization, or integration into deployed systems is intentionally
out of scope.

