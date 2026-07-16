---
layout: default
title: Genshin Damage Comparison QA Checklist
---

# Genshin Damage Comparison QA Checklist

Use this checklist before accepting a build comparison.

## Inputs

- [ ] Character and talent levels match the intended build.
- [ ] Crit rate and crit damage are not swapped.
- [ ] Percentages use the expected units.
- [ ] Weapon and artifact passives are active only when applicable.

## Target

- [ ] Enemy level is identical across builds.
- [ ] Resistance and defence assumptions are recorded.
- [ ] Reactions use the same aura and trigger.
- [ ] External buffs are held constant.

## Outputs

- [ ] Non-critical, critical, and expected-average values are saved.
- [ ] Rotation frequency is considered.
- [ ] Energy recharge requirements are included.
- [ ] One-hit damage is not presented as full-rotation output.

Re-run a clean baseline in [Genshin Damage Calculator](https://gidamagecalc.com) before adding conditional buffs.

