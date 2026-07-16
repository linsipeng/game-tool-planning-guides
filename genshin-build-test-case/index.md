# Repeatable Genshin Build Comparison Test Case

Use one controlled test case when comparing artifacts, weapons, or stat distributions. Change only the build variable being evaluated.

Calculate the relevant hits with [Genshin Damage Calculator](https://gidamagecalc.com).

## Fixed assumptions

- Character and level:
- Talent levels:
- Constellation:
- Enemy level:
- Enemy resistance:
- Reaction:
- Team buffs:
- Buff uptime:
- Rotation:

## Build A

- Weapon:
- Artifact set:
- ATK / HP / DEF as relevant:
- CRIT Rate:
- CRIT DMG:
- DMG Bonus:
- Energy Recharge:
- Important substats:

## Build B

Record the same fields. Do not improve unrelated assumptions for one build.

## Outputs

Compare:

1. Average expected damage, not only a critical hit.
2. Total damage across the meaningful rotation.
3. Time required to repeat the rotation.
4. Energy needed to maintain that rotation.
5. Performance when one optional buff is unavailable.

## Decision

Prefer the setup that performs better in the content you actually play. A larger showcase hit can be less valuable if the build loses burst availability, stable critical rate, or rotation speed.

Save this test case and reuse its fixed assumptions for the next artifact upgrade. A consistent baseline is more useful than comparing screenshots produced under different conditions.

