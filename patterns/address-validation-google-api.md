---
layout: default
title: Address validation
---

## What is it? 
__Captures customers address using a specific API;__ <br>

- Sensi API - used for postal address capture
- Weave API - used for CoM property address
- Google API - fallback API when above not available


## How does this template work? 

__On load__ <br> 
One input field is displayed. <br>
This is because this module can be combined with others, which would create longer form fields to scan.

![](img/address_start.png)


__On interaction - matched address value__
Addresses matching in drop down list. <br> 
Customer can select an address from this list.

![](img/address_matches.png)


__On interaction - no matched address value__

__No address matched__ <br>

Customer types 5 chars or more:

IF Customer enters an address string <br>
AND no match is found through the API <br>
THEN 'Enter address manually' link is displayed only <br>
AND customer can select this and display valid address  <br>

![](img/address_no_match.png)



__API unavailable__ <br>

Scenario 1:

Customer types 5 chars or more:

IF Customer enters an address string <br>
AND loses focus of address field <br>
THEN address fields expand <br>
AND address data string is cleared <br>
AND Step 4 is displayed (via expand transition)


Scenario 2:

Customer types 5 chars + address string...

IF Customer enters an address string (no match) <br>
AND hits send/next button <br>
OR Hits enter key <br>
THEN address fields expand <br>
AND address data string is cleared <br>
AND validation rules occur <br>

![](img/address_no_match.png)


__On selection of matched address__ <br>

Full fields display as read only. <br>
This is because customers were editing address and invalidating the data. 

Choose another address - goes back to 'On load' (see above)


__Enter address manually__ <br> 
Clears fields and allows data input 

![](img/address_enter_manually.png)




