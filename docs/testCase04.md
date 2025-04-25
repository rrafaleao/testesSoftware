# Edit Existing Contact
## Description: 
This test checks edit contact function on SuiteCRM

## Objective:
Test the record editing functionality, verifying that changes are saved and reflected correctly.

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
* An created contact

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Put the mouse on the 'Contacts' and click on 'Create Contact'
* Fill the blanks
* With the blanks filled, Click on 'Save'
* After saving the contact, click on Edit
* Edit some information
* Click on Save

## Expected Result:
The edited information needs to change the contact informations.

## Actual Result:
all edited information is changed and the unchanged information remains the same

## Error Description (if applicable):
No errors in system behavior.

## Evidence:
Successful test  
![successulTest](/images/testCase04/successfulTest.png)