---
layout: default
title: Minecraft Enchantment Input Field Reference
description: Preserve item identity and prior-work history in anvil planning.
---

# Minecraft Enchantment Input Field Reference

| Field | Meaning | Common mistake |
| --- | --- | --- |
| Item ID | Stable label for this exact input | Reusing a label after merging |
| Enchantments | Names and current levels | Omitting lower-level entries |
| Prior work | Previous anvil operation count | Treating identical-looking books as equal |
| Edition/version | Rules used for compatibility | Mixing Java and Bedrock assumptions |
| Target item | Final item receiving enchants | Testing an invalid item type |
| Replaceable | Whether a fresh copy is available | Spending a rare low-history input early |

Test the labeled tree with the [Minecraft Enchantment Order Calculator](https://enchantorder.com). Update the record after every real operation so the remaining costs reflect the actual inventory.
