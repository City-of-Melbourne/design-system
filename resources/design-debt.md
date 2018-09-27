---
layout: default
title: Design debt
---

There are some areas of some of the form designs whereby there are UI discrepencies. Design 'debt' term is used to describe these discrepancies.
These do not impact the UX nor the service. However, from a consistency perspective they should at some point be addressed.
This list is to record the known inconsistencies.

## Lower effort items

- Text links - Edit, Create another report, Status tracking, other (check and list)
- Error messaging - enter/provide, select/choose - terminology - Jacqueline Levan has been given access to wordpress to help DCI manage this content
- Labelling (required) vs (optional) - Illegally dumped rubbish includes an (optional) which we decided to not include
- Use of grey colour on buttons (between services. See Buttons and links)
- Submit report page - show location visual info if customer provided location via map - currently shows typed address

## Items that require more effort or consideration

- Typography
- Open/close, more/less display of content vs 'edit' (consistency on confirm step of ability to see and change content)
- Confirm Report - Contact detail capture in order to complete a service effectively - in Illegally Parked vehicles, conditional to question selection
- Edit 'bar' - parking infringements confirm page
- Layouts - Report vs P.Infringements vs Westpac (Wp needs its own)
- State and clarify H1 purpose/Initial intro copy/labels as questions (from Tims feedback on H1s as question or over arching theme of page eg. for multiple questions)
- File upload validation step is different for Infringement docs upload vs Photo upload for report services (not sure if this is really important, but noted) - Also terminology, upload, attach
- Terminology across DCI - first person, third person etc
- Loading and progress indicators - terminology, usage

## Technical items that affect user experience

- Auto-completion of address fields (Eg. location of a case or postal address for a parking infringement) currently utilises the Google Maps API. An anomaly exists if the user enters in certain types of unit numbers (Eg. "2401/318 Russell St") where the auto-complete function removes the unit number portion of the address.
