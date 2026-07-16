---
layout: default
title: Genshin Damage-Input Audit
description: Isolate the first input that causes a calculated hit to differ from an in-game test.
---

# Genshin Damage-Input Audit

Use this audit when a calculated result differs sharply from an in-game test.

1. Match character level, talent level, weapon refinement, and artifact main stats.
2. Confirm enemy level, resistance, defense reduction, and active aura.
3. Separate additive damage bonuses from reaction and amplification multipliers.
4. Verify which buffs are active at the exact hit being compared.
5. Check whether the in-game number was critical, non-critical, or averaged.

Record one reproducible hit rather than comparing an entire uncontrolled combat sequence. Remove teammates and temporary buffs that are not part of the test, then add variables back one at a time.

Enter the controlled setup in the [Genshin Impact Damage Calculator](https://gidamagecalc.com). If the values still disagree, save both the input sheet and an in-game screenshot with the same enemy and rotation state. The audit should identify the first variable that changes the result.
