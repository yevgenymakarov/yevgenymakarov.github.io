---
title: Mirror Deformer
description: Mirror Deformer for Cavalry
permalink: /plugins/mirror-deformer/
---

# Mirror Deformer

> Version 1.0.0
> Supports Cavalry 2.6.0 and later.
> **[Free Download](https://github.com/yevgenymakarov/yevgenymakarov.github.io/releases/download/v1/Mirror.Deformer.zip "Download the zip file")**
{: .py-3 .bg-gray .rounded-2 }

This plugin is a Deformer Layer that reverses the Shape along a center line to create a reflection.

## User Manual

**Strength** - Determine the strength of the Deformer.

**Offset** - Set the position of the mirror's center line.

**Rotation** - Set the angle of the mirror's orientation.

> #### EXAMPLE
> 
> 1. Create a **Text Shape** and a **Mirror Deformer**.
> 2. Connect `mirrorDeformer.id` → `textShape.deformers`.
> 3. Create a **Null**.
> 4. Connect `null.position` → `mirrorDeformer.offset`.
> 5. Connect `null.rotation.z` → `mirrorDeformer.rotation`.
> 6. Move or rotate the **Null**.
> 
> The Y-axis of the Null defines the reflection line.
{: .py-3 .bg-blue-light .border-blue-light .text-inherit .rounded-2 }

{% include plugin-install.md file_name="Mirror Deformer.zip" %}

## See Also

- [More Cavalry plugins...](../plugins.md)
