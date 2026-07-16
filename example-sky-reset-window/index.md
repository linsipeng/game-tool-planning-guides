---
layout: default
title: Sky Reset-Window Worked Example
---

# Sky Reset-Window Worked Example

## Scenario

A player has 38 minutes before daily reset and wants to finish a candle route, visit one timed event, and leave enough buffer for connection delays.

## Time budget

| Activity | Planned minutes | Latest start |
| --- | ---: | --- |
| Core candle route | 18 | T-38 |
| Timed event | 10 | T-20 |
| Return and claim | 5 | T-10 |
| Safety buffer | 5 | T-5 |

## Decision

Skip the optional realm if the timed event begins more than three minutes late. The return-and-claim step has priority because it becomes worthless after reset.

## Verification

Check the local reset and event countdown in [Sky Clock Online](https://skyclockonline.com). The plan passes only if every latest-start time remains before its displayed deadline.

