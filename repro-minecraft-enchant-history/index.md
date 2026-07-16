---
layout: default
title: Minecraft Enchantment Prior-Work Reproduction
---

# Minecraft Enchantment Prior-Work Reproduction

## Input

- Book A: fresh Sharpness IV
- Book B: Sharpness IV with two prior anvil uses
- Book C: fresh Unbreaking III
- Target: compatible sword

## Expected result

The two Sharpness books must not be treated as interchangeable because their future penalties differ.

## Reproduce

1. Give every input a stable label.
2. Enter enchantments and prior work in the [Minecraft Enchantment Order Calculator](https://enchantorder.com).
3. Compare trees using A first and B first.
4. Record total cost and final prior-work state.
5. Update labels after each simulated merge.

Pass when the cheaper valid tree preserves the low-history input where it matters.
