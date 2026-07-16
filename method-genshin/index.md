---
layout: default
title: Genshin Damage Comparison Methodology
---

# Genshin Damage Comparison Methodology

## Output model

Separate non-critical damage, critical damage, expected average, and repeatable rotation output. Each answers a different comparison question.

## Evaluation order

1. Fix character, talent, enemy, and reaction assumptions.
2. Calculate an unbuffed baseline.
3. Add stable buffs.
4. Add conditional effects only when their uptime is known.
5. Compare expected average.
6. Adjust for energy and rotation frequency.

## Assumptions

- Crit rate and crit damage use percentage inputs.
- Enemy defence and resistance remain constant between builds.
- One-hit output does not represent rotation output.
- Energy recharge matters when it changes burst frequency.

Reproduce the controlled inputs in [Genshin Damage Calculator](https://gidamagecalc.com).

