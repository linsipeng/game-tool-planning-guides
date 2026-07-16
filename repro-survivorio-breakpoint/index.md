---
layout: default
---

# Survivor.io Upgrade-Breakpoint Reproduction

## Input

- One fixed character and equipment baseline
- Upgrade A: 8% damage increase, high material cost
- Upgrade B: 5% increase, low cost
- Enemy health chosen so B reduces attacks required by one

## Expected result

Upgrade B can rank higher because it crosses the practical breakpoint at lower cost.

## Reproduce

1. Save the baseline in the [Survivor.io Calculator](https://survivoriocalc.com).
2. Duplicate it twice.
3. Change only the tested upgrade.
4. Record damage, attacks required, and resource cost.
5. Rank practical improvement per scarce resource.

Pass when the result distinguishes percentage gain from the encounter outcome.
