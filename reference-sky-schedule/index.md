---
layout: default
title: Sky Schedule Field Reference
description: Separate event times, arrival windows, and route buffers.
---

# Sky Schedule Field Reference

| Field | Meaning | Common mistake |
| --- | --- | --- |
| Device zone | Current local time zone | Assuming server time equals local time |
| Event start | Beginning of the active window | Treating it as required arrival time |
| Preferred arrival | Comfortable arrival with buffer | Scheduling every leg back-to-back |
| Latest safe arrival | Last useful entry point | Ignoring loading and travel |
| Repeat interval | Time until the next cycle | Using an outdated event cadence |
| Optional stop | Activity that can be removed | Mixing optional and required goals |

Confirm the live cycle with [Sky Clock Online](https://skyclockonline.com), then write travel and loading buffers into the route instead of storing only event timestamps.
