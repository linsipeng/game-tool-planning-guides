---
layout: default
title: Minecraft Enchantment Sequence Comparison
---

# Minecraft Enchantment Sequence Comparison

| Sequence style | Early cost | Prior-work balance | Final-step risk | Best use |
| --- | --- | --- | --- | --- |
| Apply books one by one | Low | Poor | High | Very few clean books |
| Balanced book tree | Medium | Strong | Low | Many fresh books |
| Combine onto used item early | Variable | Poor | High | Only when item history is low |
| Clean-book-first tree | Medium | Strong | Medium | Known book histories |
| Mixed orientation search | Variable | Best possible | Lowest after comparison | Minimise total cost |

## Decision rules

- Preserve actual prior-work values.
- Compare both anvil orientations.
- Cost at least two pairing trees.
- Verify every intermediate step is legal.

Model each sequence in [Minecraft Enchant Order](https://enchantorder.com).

