---
layout: default
title: Sky Schedule Planning Methodology
---

# Sky Schedule Planning Methodology

## Time model

Represent a session as fixed deadlines plus variable activity and travel durations. Daily reset, event start, and event end are separate boundaries.

## Evaluation order

1. Confirm local timezone and device time.
2. Record reset and event windows.
3. Subtract travel and participation time.
4. Protect claim and return steps.
5. Allocate optional activities only from the remaining buffer.
6. Recalculate after a late start.

## Assumptions

- Travel includes loading and navigation.
- Exact-fit schedules have zero resilience.
- Reset-sensitive value is prioritised over optional collection.
- A fallback route is selected before the session begins.

Use live countdowns from [Sky Clock Online](https://skyclockonline.com) as the current timing reference.

