# Integration with the Sales Module
## Description: 
test suiteCRM's lead creation and management (edit, delete) functionality, test the integration with contact and tasks too.

## Objective: 
Test the creation and management of sales opportunities, checking the integration with other modules such as contacts and tasks.  

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Put the mouse on 'More' in the topbar.
* Search for 'Leads' and click on it
* Go to 'Create lead'
* Fill all the blanks and click on save 

## Expected Result:
* Software needs to create a Lead, and it need to be seem on the 'view lead' section
* Need to be possible delete a created lead
* Need to be possible to Edit a lead

## Actual Result:
* It is possible to create a lead.
* Delete function is working correctly
* Edit function is working correctly

## Result Analysis:
The lead sistem on SuiteCRM software is all working perfectualy, with all the functions doing his own job correctly.

## Error Description (if applicable):
No errors in system behavior.

## Evidence:
* Created leads  
![Created leads](/images/testCase21/createdLeads.png)  

* Edit Lead  
![editedLead](/images/testCase21/editedLead.png)  

* Delete lead  

![deletedLead](/images/testCase21/deletedLead.png)  