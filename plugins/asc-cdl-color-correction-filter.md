---
title: ASC-CDL Color Correction
description: ASC-CDL Color Correction Filter for Cavalry
permalink: /plugins/asc-cdl-color-correction-filter/
---

# ASC-CDL Color Correction

> Version 1.0.0
> Supports Cavalry 2.4.3 and later.
> **[Free Download](https://github.com/yevgenymakarov/yevgenymakarov.github.io/releases/download/v1/ASC-CDL.Color.Correction.Filter.zip "Download the zip file")**
{: .py-3 .bg-gray .rounded-2 }

This plugin is a Filter Layer that adjusts the colors using Slope, Offset, and Power functions, with an additional Saturation parameter.

## User Manual

**Slope** - Multiplies the input color values and adjusts the highlights.

**Offset** - Adds a value to the result of the slope multiplication, affecting the overall brightness.

**Power** - Applies a power function to the values after the slope and offset, modifying the midtones of the image.

**Saturation** - Provides a weighted average of the normal color and fully de-saturated images.

{% include plugin-install.md file_name="ASC-CDL Color Correction Filter.zip" %}

## See Also

- [More Cavalry plugins...](../plugins.md)
