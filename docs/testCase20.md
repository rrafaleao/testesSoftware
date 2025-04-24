# Validation of Mandatory Fields
## Description: 
Check the system mandatory fields, see if it's possible to create a report without filling this blanks.

## Objective: 
Check whether the system prevents saving reports with blank mandatory fields, displaying appropriate error messages.

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Put the mouse on 'More' in the topbar.
* Look for 'reports' and click on it.
* Then, go to create reports.
* Without filling the blanks, click on save.
* Then, filling each essential blank at a time.

## Expected Result:
* Should not be possible create a report without all the essential blanks being filled;
* Software needs to show what blank is essencial and what is unfilled.

## Actual Result:
* System show a error message when a essential blank is empty
* It is not possible to create a report without all the essential blanks.

## Result Analysis:
SuiteCRM fulfills its function of not being possible to add a report empty or without some essential field

## Error Description (if applicable):
No errors in system behavior.

## Evidence:

* Essential blanks  
![emptyFields](/images/testCase20/emptyFields.png)  