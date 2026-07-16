---
layout: default
title: Minecraft Enchantment Order Methodology
---

# Minecraft Enchantment Order Methodology

## Cost model

Each item carries enchantments and a prior-work history. A sequence must minimise total cost while keeping every intermediate operation legal.

## Evaluation order

1. Record every item and prior-work value.
2. Remove incompatible combinations.
3. Test both left-right orientations.
4. Build balanced book-pair trees.
5. Compare total cost and final-step cost.
6. Verify the chosen sequence step by step.

## Assumptions

- Visible enchantments do not reveal prior work.
- Prior-work penalties move to the resulting item.
- Renaming and other added operations affect cost.
- The cheapest final step may not produce the cheapest sequence.

Enter real item histories in [Minecraft Enchant Order](https://enchantorder.com).

