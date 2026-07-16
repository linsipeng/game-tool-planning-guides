---
layout: default
title: Genshin Rotation Comparison Worked Example
---

# Genshin Rotation Comparison Worked Example

## Scenario

Two artifact builds have similar critical value. Build A has higher displayed damage, while Build B has enough energy recharge to cast the burst every rotation.

## Inputs

| Field | Build A | Build B |
| --- | ---: | ---: |
| Attack | 2,080 | 1,940 |
| Crit rate | 72% | 75% |
| Crit damage | 188% | 176% |
| Energy recharge | 112% | 138% |
| Burst interval | Every second rotation | Every rotation |

## Decision

Compare damage over two complete rotations, not a single critical hit. Build B wins if its second burst exceeds the difference in normal and skill damage.

## Verification

Recreate both input sets in [Genshin Damage Calculator](https://gidamagecalc.com) and record non-critical, critical, and expected-average results without changing buffs between builds.

