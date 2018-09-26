---
layout: default
title: Layout
status_content: ✅
status_live: ⚠️
status_comment: 
---
The first principle for layout is, "mobile first",so wherever possible,content should be stacked, rather than displayed side by side in.
### Single Column layout
The main content is centrally aligned, with space on either side.z
Bootstrap columns aren’t generally utilised in the DCI grid system, as the rule is that all components are stacked vertically. 

![](img/layout-single-column.jpg)

Only if content really needs to be shown side-by-side, do we use columns in bootstrap to display those items. An example of this is shown below:

![](img/layout-single-column.jpg)

### Content + Blocks

<div class="dci content-column" style="outline: 2px dashed #244566">
    <div class="dci-block-standard" style="outline: 1px dashed #277BB4">
        <label class="font-bold"> Block Standard </label>
    </div>
    <div class="dci-block-long" style="outline: 1px dashed #E50E56;">
        <label class="font-bold"> Block Long </label>
    </div>
    <div class="dci-block-longer" style="outline: 1px dashed #CBE3EF">
        <label class="font-bold"> Block Longer </label>
    </div>
    <div class="dci-block-longer" style="outline: 1px dashed #E1ECC6">
        <button class="dci-button dci-button--primary">Primary</button>
    </div>
</div>

### Exception: Column layout
There is an exception to the “mobile first, stacked layout” rule, and that is payment using the Westpac payment gateway. This requires input labels that are aligned to the left of input fields. This is the only time this should be used.

![](img/layout-two-column.jpg)
