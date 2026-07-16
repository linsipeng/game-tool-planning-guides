---
layout: default
title: Genshin Damage Result Recovery Decision Tree
---

# Genshin Damage Result Recovery Decision Tree

Use this tree when a damage result is unexpectedly high, low, or inconsistent across builds.

1. Is non-critical damage wrong?
   - Yes: inspect attack, talent multiplier, damage bonus, defence, and resistance.
   - No: continue to critical fields.
2. Is only critical damage wrong?
   - Yes: verify crit damage was entered as a percentage and not swapped with crit rate.
   - No: inspect expected average.
3. Is expected average outside the non-critical and critical range?
   - Yes: reset crit fields and rerun.
   - No: compare buff states.
4. Do the two builds use identical enemy and buff assumptions?
   - No: align them.
   - Yes: compare complete rotations rather than one hit.

Re-enter the clean baseline in [Genshin Damage Calculator](https://gidamagecalc.com) before adding buffs one at a time.

