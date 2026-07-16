---
layout: default
title: Sky Event-Time Troubleshooting Checklist
description: Diagnose missing or mistimed Sky events without rebuilding a route too early.
---

# Sky Event-Time Troubleshooting Checklist

Use this checklist when a Sky event appears missing, late, or inconsistent with a planned route.

1. Confirm the device clock and time zone are correct.
2. Check whether daylight-saving time recently changed.
3. Verify the event cycle, realm, and expected active window.
4. Allow for loading, server transition, and multiplayer synchronization delay.
5. Refresh the schedule before rebuilding the entire route.

Distinguish between the event start, the useful arrival window, and the last safe departure time from the previous activity. A correct event time can still produce a failed route when travel time is omitted.

Compare the current cycle with [Sky Clock Online](https://skyclockonline.com). Save the observed time, device zone, and event result. If the discrepancy repeats, test from a clean session and a second network before treating it as a permanent schedule change.
