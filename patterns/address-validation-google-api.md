---
layout: default
title: Address validation
---

## Address validation 

### What is it? 
__Captures customers address using a specific API;__ <br>

- Sensi API - used for postal address capture
- Weave API - used for CoM property address
- Google API - fallback API when above not available


### How does this template work? 

## On load <br> 
One input field is displayed.
This is because this module can be combined with others, which would create longer form fields to scan.

![](img/address_start.png)


## On interaction - matched address value
Addresses matching in drop down list. <br> 
Customer can select an address from this list.

![](img/address_matches.png)


## On interaction - no matched address value

__No address matched__ <br>

Customer types 5 chars or more:

IF Customer enters an address string
AND no match is found through the API
THEN 'Enter address manually' link is displayed only
AND customer can select this and display valid address 

![](img/address_no_match.png)



__API unavailable__ <br>

Scenario 1

Customer types 5 chars or more:

IF Customer enters an address string
AND loses focus of address field
THEN address fields expand
AND address data string is cleared
AND Step 4 is displayed (via expand transition)


Scenario 2

Customer types 5 chars + address string...

IF Customer enters an address string (no match)
AND hits send/next button
OR Hits enter key
THEN address fields expand
AND address data string is cleared
AND validation rules occur

![](img/address_no_match.png)


__On selection of matched address__ <br>

Full fields display as read only. 
This is because customers were editing address and invalidating the data. 

Choose another address - goes back to 'On load' (see above)


__Enter address manually__ <br> 
Clears fields and allows data input 

![](img/address_enter_manually.png)




