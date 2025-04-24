# System Log Verification and Auditing
## Description: 
Test if the SuiteCRM is creating logs correctly.

## Objective: 
Validate whether the system correctly records user actions, allowing auditing of operations performed (login, creation, editing and deletion).

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
* Then edit the lead.
* Then delete the lead.
* Go to the dashboard and see if the software registered it on his logs

## Expected Result:
* Should appear all the thing that the user create, edit and delete on SuiteCRM

## Actual Result:
* It appears all the things that are created
* Does not appear when you edit or delete a contact

## Result Analysis:
It works when you create a contact, lead, etc. But does not work when you delete or edit it.

## Error Description (if applicable):
It not register when you delete or edit a thing on SuiteCRM software.

## Evidence:
* No edit or delete on logs  
![logTest](/images/testCase22/logTest.png)  

![logTest2](/images/testCase22/logTest2.png)  