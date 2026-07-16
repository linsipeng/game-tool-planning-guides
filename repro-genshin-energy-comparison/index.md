---
layout: default
title: Genshin Energy-Constrained Build Reproduction
---

# Genshin Energy-Constrained Build Reproduction

## Input

- Same character, enemy, team buffs, and rotation
- Build A: higher critical damage, lower recharge
- Build B: lower critical damage, enough recharge to repeat burst
- Test window: two complete rotations

## Expected result

Build A may win one hit but must include extra waiting or skill time if its second burst is late.

## Reproduce

1. Enter the shared baseline in the [Genshin Impact Damage Calculator](https://gidamagecalc.com).
2. Change only the artifact and recharge fields.
3. Record first-rotation damage.
4. Add the time required to restore the second burst.
5. Compare total damage over the full window.

Pass when the conclusion states both damage and the energy condition needed to repeat it.
