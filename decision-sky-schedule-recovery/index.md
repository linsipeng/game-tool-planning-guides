---
layout: default
title: Sky Schedule Recovery Decision Tree
---

# Sky Schedule Recovery Decision Tree

Use this tree when an event route is late or a reset calculation looks wrong.

1. Is the displayed timezone correct?
   - No: correct it before changing the route.
   - Yes: compare the displayed reset with the local clock.
2. Is the event still active after travel time?
   - Yes: subtract a safety buffer and continue.
   - No: skip it and preserve the reset-sensitive claim.
3. Did the event start late?
   - No: follow the planned sequence.
   - Yes: shorten optional activities, not the return step.
4. Is the remaining window an exact fit?
   - No: label it safe with the measured buffer.
   - Yes: label it risky and choose the fallback route.

Confirm the corrected event and reset window in [Sky Clock Online](https://skyclockonline.com).

