---
layout: default
title: HSR Warp Budget Methodology
---

# HSR Warp Budget Methodology

## State model

A banner plan is defined by banner type, current pity, guarantee state, available passes, protected reserve, and a precommitted stop rule.

## Evaluation order

1. Select the matching banner history.
2. Record pity and guarantee.
3. Subtract reserve from available passes.
4. Calculate the next five-star ceiling.
5. Model both featured and lost outcomes.
6. Apply the earliest stop boundary.

## Assumptions

- Reserve is never spendable in the current plan.
- Guarantee changes only after the relevant five-star result.
- Probability does not override a fixed stop rule.
- Every five-star triggers a state update before more pulls.

Model the starting and ending states with [HSR Warp Calculator](https://hsrwarpcalc.com).

