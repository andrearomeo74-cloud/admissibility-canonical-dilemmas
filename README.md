# Admissibility Canonical Dilemmas

This repository collects a set of canonical technical dilemmas that appear unrelated,
yet share the same structural cause: a missing criterion of admissibility.

Core idea:
Not everything that is technically possible, coherent, or optimizable
remains admissible once scale, cost, and complexity are included.

---

## Admissibility Principle

We use a minimal, domain-agnostic index:

CI = V / (E + I + S)

where:
- V: effective value produced by the system
- E: energetic/material cost
- I: informational/organizational burden
- S: scaling overhead (degrees of freedom, actors, time horizon, interactions)

A system remains viable only while CI stays above a context-dependent threshold.
When the threshold is crossed, the system changes regime.

---

## Admissibility via Invariants (physics analogy)

In physics, **invariants** constrain the space of admissible states *before* any dynamics is considered.
A classic example is the relativistic energy–momentum relation, which restricts what can be physically consistent.

This repository uses the same structural idea:
- we do not optimize trajectories first and then “fix” inconsistencies,
- we **constrain the state space ex-ante** using a minimal admissibility index.

**Congruity / Admissibility is a law-of-limits framing, not an optimization recipe.**
It answers: *which states are structurally viable once cost, scale, and complexity are accounted for?*

## How to Use This Repo

1. Read `start_here.md`
2. Read dilemmas in order under `dilemmas/`
3. Use `unifying_principle.md` as the final compression layer

---

## What This Is / Is Not

This is:
- a law-of-limits framing (admissibility), not an optimization recipe
- a cross-domain map of regime transitions

This is not:
- a new physical theory
- a replacement for existing domain models
- policy advocacy
