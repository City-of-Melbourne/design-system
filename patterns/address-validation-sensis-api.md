---
layout: default
title: Address validation + Sensis API
status_content: ✅
status_live: ⚠️
status_comment:
---

## What is it?
Captures customers valid postal address.
## How does this template work?

### 1.On Page load

One input field is displayed.

This is because this module can be combined with others, which would create longer form fields to scan.

![](img/address_vali_sensis1.png)


### 2.On Page load - __IF SENSIS API NOT AVAILABLE__

__API unavailable - scenarios__

Scenario 1
__Customer types 5 chars or more:__

IF Customer enters an address string
AND loses focus of address field
THEN address fields expand
AND address data string is cleared
AND Step 4 is displayed (via expand transition)

Scenario 2
__Customer types 5 chars + address string...__

IF Customer enters an address string (no match)
AND hits send/next button
OR Hits enter key
THEN address fields expand
AND address data string is cleared
AND validation rules occur

![](img/address_vali_sensis2.png)


### 3.Type address (no match)

__No address matched - scenario__

Scenario 1
__Customer types 5 chars or more:__

IF Customer enters an address string
AND no match is found through the API
THEN 'Enter address manually' link is displayed only
AND customer can select this link and go to Step 6

![](img/address_vali_sensis2.png)


### 4.Type address (match)

Addresses matching in drop down list.
Customer can select an address from this list.

![](img/address_vali_sensis3.png)


### 5.Fields are populated upon selecting match

Choose another address - goes back to Step 1
Enter address manually - goes to Step 6

![](img/address_vali_sensis4.png)

### 6.Enter address manually

Choose another address - goes back to Step 1

![](img/address_vali_sensis5.png)


## Where is it used?

- __Graffiti__ [https://test.services.melbourne.vic.gov.au/report/graffiti](https://test.services.melbourne.vic.gov.au/report/graffiti)  __No__  
- __Tree Maintenance__ [https://test.services.melbourne.vic.gov.au/report/treemaintenance](https://test.services.melbourne.vic.gov.au/report/treemaintenance)  __No__
- __Abandoned Vehicle__ [https://test.services.melbourne.vic.gov.au/report/abandonedvehicle ](https://test.services.melbourne.vic.gov.au/report/abandonedvehicle )  __No__
- __Illegally Parked Vehicle__ [https://test.services.melbourne.vic.gov.au/report/illegallyparkedvehicle](https://test.services.melbourne.vic.gov.au/report/illegallyparkedvehicle)  __No__
- __Syringe Management__ [https://test.services.melbourne.vic.gov.au/report/syringemanagement](https://test.services.melbourne.vic.gov.au/report/syringemanagement)  __No__
- __Illegally Dumped Rubbish__ [https://test.services.melbourne.vic.gov.au/report/illegallydumpedrubbish](https://test.services.melbourne.vic.gov.au/report/illegallydumpedrubbish)  __No__
- __Rough Sleeping__ [https://test.services.melbourne.vic.gov.au/tellus/online](https://test.services.melbourne.vic.gov.au/tellus/online)  __No__
- __Parking Infringement Review__ [https://test.services.melbourne.vic.gov.au/ask/infringementreview](https://test.services.melbourne.vic.gov.au/ask/infringementreview)  __Yes__
- __Animal Infringement Review__ [https://test.services.melbourne.vic.gov.au/ask/animals/infringementreview](https://test.services.melbourne.vic.gov.au/ask/animals/infringementreview)  __Yes__
- __Local Law Infringement Review__ [https://test.services.melbourne.vic.gov.au/ask/locallaws/infringement](https://test.services.melbourne.vic.gov.au/ask/locallaws/infringement)  __Yes__
- __General Enquiry__ [https://test.services.melbourne.vic.gov.au/ask/question](https://test.services.melbourne.vic.gov.au/ask/question)  __No__



