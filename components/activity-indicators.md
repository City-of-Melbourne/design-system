---
layout: default
title: Activity Indicators
---

TODO: Add description

### Form progress indicator

Indicates how many steps there are to complete form. Highlights which step customer is currently on

![](img/steps_graphic.png)

```
.steps-wizard .wizard-progress .step.future {
 background-image: url(/images/wizard-progress-future.png);
}
dci.wizard.css:100
.steps-wizard .wizard-progress .step {
 width: 20px;
 height: 20px;
 color: #50535d;
 background: url(/images/wizard-progress-future.png) 100% 100% no-repeat;
 display: inline-block;
 margin: 0 4px;
 font-size: 14px;
 font-weight: 700;
 background-size: 100% 100%;
 background-repeat: no-repeat;
 line-height: 1.5;
 text-decoration: none;

```

### Progress bar

TODO: extract from [patterns/loading-and-processing-indicators.html](patterns/loading-and-processing-indicators.html)

### Loader/Spinner

TODO: extract from [patterns/loading-and-processing-indicators.html](patterns/loading-and-processing-indicators.html)
