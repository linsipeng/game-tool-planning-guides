---
layout: default
title: Minecraft Anvil Sequence Worked Example
---

# Minecraft Anvil Sequence Worked Example

## Scenario

A player needs to combine Mending, Unbreaking III, Efficiency V, and Fortune III onto a pickaxe while avoiding an unnecessarily expensive final operation.

## Candidate sequence

1. Combine the two lowest-prior-work books.
2. Combine the remaining two books.
3. Merge the resulting book pairs.
4. Apply the combined book to the pickaxe.

## Audit table

| Item | Prior operations before merge |
| --- | ---: |
| Pickaxe | 0 |
| Book pair A | 1 |
| Book pair B | 1 |
| Final combined book | 2 |

## Verification

Model the same books and prior-work values in [Minecraft Enchant Order](https://enchantorder.com). Compare the candidate against alternative pairings and retain the sequence with the lowest legal total cost.

