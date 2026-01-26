# Control Instability and the Absence of an Arrest Criterion

## The Canonical Dilemma

Modern control theory provides powerful tools to stabilize systems,
reduce error, and optimize performance through feedback.

Yet a recurring phenomenon appears across domains:
systems that are locally controllable become globally unstable
when control intensity, feedback frequency, or system scale increases.

The classical explanation invokes non-linearity, chaos,
or sensitivity to initial conditions.

This explanation is correct, but incomplete.

---

## What Control Theory Explains

Standard control theory explains:
- how feedback reduces error locally,
- how stability can be ensured within bounded regimes,
- how optimal controllers minimize cost functions.

These tools describe *how to control a system*.

They do not define *when control itself should stop*.

---

## The Missing Question

The unresolved question is not how to improve control,
but when continued control becomes illegitimate.

There is no general criterion indicating when:
- additional sensing degrades stability,
- faster feedback amplifies oscillations,
- stronger actuation induces systemic fragility.

Control theory lacks an admissibility boundary.

---

## Admissibility Reframing

From an admissibility perspective, instability does not arise
because the system is chaotic,
but because control has exceeded a viable regime.

We express this condition schematically as:

CI = V / (E + I + S)

where:
- V represents the effective performance gain,
- E the energetic cost of actuation,
- I the informational burden of sensing and feedback,
- S the scale of the controlled system (states, latency, coupling).

---

## Regime Transition

As informational burden and scale grow,
the marginal value of control diminishes.

When CI falls below the admissibility threshold:
- feedback ceases to stabilize,
- oscillations and instabilities emerge,
- optimal control becomes destructive.

Instability marks a transition of regime,
not a failure of design.

---

## Why This Matters

This reframing explains why:
- additional control often worsens performance,
- highly optimized systems become brittle,
- global optimization destabilizes local equilibria.

The failure is not technical error,
but the absence of a stopping rule.

Control instability emerges when admissibility is lost,
not when control theory is violated.
