---
layout: default
title: Layout
status_content: ✅
status_live: ⚠️ 
status_comment: Live example needs 
---

The first principle for layout is, "mobile first", so wherever possible, content should be stacked, rather than displayed side by side in.

### Single Column layout

The main content is centrally aligned, with space on either side. The max width for this main content is 355px, and when the viewport window is less than 768px, it breaks to 300px max width.

Bootstrap columns aren’t generally utilised in the DCI grid system, as the rule is that all components are stacked vertically. 

![](img/layout-single-column.jpg)

Only if content really needs to be shown side-by-side, do we use columns in bootstrap to display those items. An example of this is shown below:

![](img/layout-single-column.jpg)

### Raw Layout(Without Header and Footer)
<div class="body-content-wrapper" style="outline: 2px dashed #6ce00d">
    <div class="body-content" style="outline: 2px dashed #2d90f3">
        <div class="page-title">Layout Example</div>
        <section id="LocationStep" class="container wizard-step wizard-step-first ">
            <form class="steps-wizard" method="post" style="outline: 2px dashed #7a0c6c;width: 906px">
                <div class="wizard-progress" style="outline: 2px dashed #83c0fd;width: 906px">
                    <span class="step current">1</span>
                    <span class="step future">2</span>
                    <span class="step future">3</span>
                    <span class="step future">4</span>
                    <span class="step future">5</span>
                    <span class="step future">6</span>
                </div>
                <div class="page-heading-container" style="outline: 2px dashed #0f60b1;width: 906px">
                    <div class="content-column">
                        <div class="page-title">Title</div>
                    </div>
                    <div class="gradient-separator"></div>
                </div>
                <div class="content-column">

                    <section class="location-sub-step">
                        <div class="label-style">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam placerat mauris sed nunc ultricies </div>
                        <div class="wizard-buttons-container">Buttons Here</div>
                    </section>
                </div>
            </form>
        </section>
    </div>
</div>

### Content + Blocks

<div clas="dci-content-column" style="outline: 2px dashed #244566">
        <div class="dci dci-block-standard" style="outline: 1px dashed #277BB4">
            <label class="font-bold"> Block Standard </label>
        </div>
        <div class="dci dci-block-long" style="outline: 1px dashed #E50E56;">
            <label class="font-bold"> Block Long </label>
        </div>
        <div class="dci dci-block-longer" style="outline: 1px dashed #CBE3EF">
            <label class="font-bold"> Block Longer </label>
        </div>
        <div class="dci dci-block-longer" style="outline: 1px dashed #E1ECC6">
            <button class="dci-button dci-button--primary">Primary</button>
        </div>
    </div>

### Exception: Column layout

There is an exception to the “mobile first, stacked layout” rule, and that is payment using the Westpac payment gateway. This requires input labels that are aligned to the left of input fields. This is the only time this should be used.

![](img/layout-two-column.jpg)
