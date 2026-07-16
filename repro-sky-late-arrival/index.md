---
layout: default
title: Sky Late-Arrival Reproduction
---

# Sky Late-Arrival Reproduction

## Input

- Session length: 30 minutes
- Required event: begins in 18 minutes
- Direct travel estimate: 6 minutes
- Loading and coordination buffer: 4 minutes
- Optional activity: 7 minutes

## Expected result

The optional activity must be skipped because it would push arrival beyond the safe window.

## Reproduce

1. Confirm the event cycle in [Sky Clock Online](https://skyclockonline.com).
2. Calculate preferred and latest safe arrival.
3. Add travel and loading buffers.
4. Insert the optional activity.
5. Remove it when the projected arrival crosses the latest safe time.

Pass when the route preserves the required event without assuming zero loading or travel delay.
