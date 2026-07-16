---
layout: default
title: Minecraft Image Output Recovery Decision Tree
---

# Minecraft Image Output Recovery Decision Tree

Use this tree when converted art loses transparency, detail, or palette compliance.

1. Did transparent pixels become blocks?
   - Yes: restore an alpha-enabled source and re-import.
   - No: inspect dimensions.
2. Is the output stretched?
   - Yes: lock aspect ratio before resizing.
   - No: inspect palette restrictions.
3. Are disallowed blocks present?
   - Yes: select the intended survival or block-family palette.
   - No: inspect detail loss.
4. Is a small emblem unreadable?
   - Yes: reduce dithering or protect the emblem region.
   - No: export the material list.

Repeat one change at a time in [Minecraft Image Art](https://mcimgart.com) so the preview difference has a clear cause.

