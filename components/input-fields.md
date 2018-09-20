---
layout: default
title: Input Fields
---

Browser display: __Desktop__ - Input displays at width: 355px, height: 38px; | __Mobile__ - Input displays at width: 300x, height: 38px;

## Single line text field - generic text capture

### Input and error
![](img/Components_text_input_single_line.png) 

<div class="dci">

  <label class="font-bold"> Label </label> <label class="font-regular">(required)</label>
  
  <input type="text" id="test" class="dci-input-text" name="query">
    

  
  <label class="font-bold"> Label </label> <label class="font-regular">(required)</label>
 
  
    <input type="text" id="test" class="dci-input-text in-error" name="query">
    <span style="color:#e50e56;display:block;font-weight: 400;" >You must provide your email address or mobile number</span>
    

  

</div>
  

### What it does 
- Captures text data, un-formatted.
- Displays error text upon validation rules not met when mandatory and marked as (required)

## Single line text field - mobile phone number capture

### What it does 
- Captures mobile phone numbers, formatted to standard AU mobile numbers
- Displays error text upon validation rules not met when mandatory and marked as (required)

### Validation Rules
- Must start with 04
- Must be numeric
- Must contain 10 digits

## Multi-line text field + description - generic text capture

### What it does 
- Captures any additional alpha numberic data
- Displays error text upon validation rules not met when mandatory and marked as (required)

### Input
![](img/multiline_text_field.png)  

### Error
## Dropdown list - selection capture
### What it does
### Input
### Error
## Radio button list - selection capture
### What it does
### Input
![](img/radio.png)  
### Error
![](img/radio_error.png) 
## Checkbox list - selection capture
### What it does 
- Captures multiple answers and helps direct the Case to a team or contractor.

### Input
![](img/checklist.png)  
### Error
![](img/checklist_error.png) 

