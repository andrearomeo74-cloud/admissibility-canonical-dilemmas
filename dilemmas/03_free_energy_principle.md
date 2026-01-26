# Free Energy Minimization and Admissibility Breakdown

## The Canonical Dilemma

The Free Energy Principle (FEP) proposes that adaptive systems
maintain their integrity by minimizing variational free energy.

This idea has been applied broadly to:
- biological organisms,
- neural systems,
- cognition and behavior,
- artificial agents.

The principle successfully explains local adaptation
and short-term stability.

Yet a persistent problem remains.

---

## The Unresolved Issue

If minimizing free energy is fundamentally stabilizing,
why do many systems that strongly minimize it
become rigid, pathological, or fragile over time?

Examples include:
- cognitive overfitting and anxiety,
- behavioral rigidity,
- maladaptive prediction loops,
- systems that prefer certainty over viability.

The classical framework does not provide
a criterion for when minimization itself becomes harmful.

---

## What the FEP Explains

The Free Energy Principle explains:
- how prediction error is reduced,
- how internal models align with sensory input,
- how systems resist surprise locally.

It explains *how* adaptation proceeds.

It does not explain *when continued adaptation
ceases to be admissible*.

---

## The Missing Boundary

The principle lacks a stopping condition.
It assumes that continued minimization
always contributes to viability.

This assumption fails at scale.

Without an admissibility boundary,
systems can optimize themselves
into non-viable states.

---

## Admissibility Reframing

From an admissibility perspective,
free energy minimization remains valid
only while its informational and energetic costs
remain proportionate to the value it produces.

We express this schematically as:

CI = V / (E + I + S)

where:
- V represents adaptive value and functional stability,
- E the energetic cost of sustaining the model,
- I the informational complexity of prediction and inference,
- S the temporal and environmental scale of model deployment.

---

## Regime Transition

As models become more complex and operate across broader scales,
informational and energetic burdens grow super-linearly.

When CI falls below the admissibility threshold:
- prediction dominates action,
- uncertainty avoidance replaces exploration,
- the system becomes brittle.

Pathology emerges not from insufficient adaptation,
but from over-adaptation beyond admissible limits.

---

## Why This Matters

This reframing explains why:
- excessive prediction leads to loss of flexibility,
- minimizing surprise can reduce long-term viability,
- optimal inference can produce maladaptive behavior.

The failure lies not in the principle,
but in the absence of an admissibility criterion.

Free energy minimization becomes destructive
when applied beyond the scale at which it is viable.
