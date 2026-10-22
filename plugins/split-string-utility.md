---
title: Split String
description: Split String Utility for Cavalry
permalink: /plugins/split-string-utility/
---

# Split String

> Version 1.0.0
> Supports Cavalry 2.7.2 and later.
> **[Free Download](https://github.com/yevgenymakarov/yevgenymakarov.github.io/releases/download/v1/Split.String.Utility.zip "Download the zip file")**
{: .py-3 .bg-gray .rounded-2 }

This plugin is a Utility Layer that splits the entered string (text) into sub-strings by the selected delimiter and procedurally creates a list of strings which can be assigned to other layers via their indices, similar to the String Array.

## User Manual

**Input String** - Enter the text to be split into an array.

**Mode** - Select a method for splitting the source text. You can split by characters, words, newlines, commas, or tabs.

**Skip Empty** - Do not add blank strings to the final array.

**Auto Index** - Automatically output all indices within the array.

**Index** - Manually output an index within the array (uncheck Auto Index to enable).

**Reverse** - Invert the order the indices are output in.

> #### EXAMPLE
> 
> 1. Create a **Text Shape**.
> 2. Right click on the **String** attribute and choose **Add Utility** → **Split String**.
> 3. Enter `ABCDEFGHIJKLMNOPQRSTUVWXYZ` into **Input String**.
> 4. With the **Text Shape** selected, click the **Duplicator** icon in the **Shelf**.
> 
> Each duplicated Text Shape is given its own alphabet character.
{: .py-3 .bg-blue-light .border-blue-light .text-inherit .rounded-2 }

{% include plugin-install.md file_name="Split String Utility.zip" %}

## See Also

- [More Cavalry plugins...](../plugins.md)
