---
layout: default
title: Input Fields
status_content: ⚠️
status_live: ✅
status_comment: Dropdown component pending (Content and HTML)
---

Browser display: __Desktop__ - Input displays at width: 355px, height: 38px; | __Mobile__ - Input displays at width: 300x, height: 38px;

## Single line text field - generic text capture

### Input and error


<div class="dci">


  <label class="font-bold"> Label </label> <label class="font-regular">(required)</label>  
  <input type="text"  class="dci-input-text" >
  
    <label class="font-bold"> Label </label> <label class="font-regular">(required)</label>
    <input type="text"  class="dci-input-text in-error" >
    <span  class="dci-validation in-error">Error message appears on validation</span>
    
</div>
  

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
<div class="dci">
  <label class="font-bold"> Do you have any further information to help us action your request? </label>   
  <textarea  class="dci-input-text" name="query" rows="15"></textarea> 
</div>

### Error
## Dropdown list - selection capture
TODO
### What it does
### Input
### Error
## Radio button list - selection capture
### What it does
### Input


<div class="dci">
    <fieldset class="dci-radiobuttons"> 
      <legend > 
          <span class="font-bold"> Is the rubbish in a park?</span>
          <span class="font-regular">(required)</span>
      </legend>   
              <div class="dci-radiobutton"> <input type="radio"><label>Yes</label></div>
              <div class="dci-radiobutton"> <input type="radio"><label >No</label> </div>      
    </fieldset>
</div>

### Error

<div class="dci">
<fieldset class="dci-radiobuttons"> 
  <legend > 
      <span class="font-bold"> Is the rubbish in a park?</span>
      <span class="font-regular">(required)</span>
  </legend>   
          <div class="dci-radiobutton"> <input type="radio"><label>Yes</label></div>
          <div class="dci-radiobutton"> <input type="radio"><label >No</label> </div> 
          <span class="dci-validation in-error" >Please select an option</span>
</fieldset>
</div>


## Checkbox list - selection capture
### What it does 
- Captures multiple answers and helps direct the Case to a team or contractor.

### Input
<div class="dci">
<fieldset class="dci-checkboxes"> 
  <legend > 
      <span class="font-bold"> You cant select more than one answer. If you're unsure,please select other?</span>
      <span class="font-regular">(required)</span>
  </legend>   
          <div class="dci-checkbox"><input  type="checkbox" ><label>Bags of rubbish </label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Mattress(es)</label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Hard waste, for example furniture or electrical appliances </label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Cardboard boxes</label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Construction waste</label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Other</label></div>
                    
</fieldset>
</div>

### Error

<div class="dci">
<fieldset class="dci-checkboxes"> 
  <legend > 
      <span class="font-bold"> You cant select more than one answer. If you're unsure,please select other?</span>
      <span class="font-regular">(required)</span>
  </legend>   
          <div class="dci-checkbox"><input  type="checkbox" ><label>Bags of rubbish </label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Mattress(es)</label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Hard waste, for example furniture or electrical appliances </label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Cardboard boxes</label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Construction waste</label></div>
          <div class="dci-checkbox"><input  type="checkbox" ><label>Other</label></div>
          
          <span class="dci-validation in-error" >Please select an option</span>
</fieldset>
</div>

