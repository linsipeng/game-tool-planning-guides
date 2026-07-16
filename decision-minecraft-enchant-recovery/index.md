---
layout: default
title: Minecraft Enchantment Cost Recovery Decision Tree
---

# Minecraft Enchantment Cost Recovery Decision Tree

Use this tree when an anvil sequence is too expensive or becomes illegal.

1. Is the enchantment combination compatible?
   - No: remove the conflicting book.
   - Yes: inspect prior-work values.
2. Was a high-prior-work item combined early?
   - Yes: move it later and compare again.
   - No: test balanced book pairs.
3. Does reversing the left and right inputs change cost?
   - Yes: retain the cheaper legal orientation.
   - No: compare a different pairing tree.
4. Does the final step exceed the legal limit?
   - Yes: restart from the lowest-prior-work items.
   - No: save the sequence and total.

Enter each item’s real history in [Minecraft Enchant Order](https://enchantorder.com); identical enchantments can still have different prior-work penalties.

