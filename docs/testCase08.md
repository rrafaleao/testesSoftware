# Data Export
## Description: 
Test if the SuiteCRM can export a contact to csv.

## Objective: 
Ensure that the log export works properly and that the generated file contains the correct data.

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
* A Contact to made the Exportation

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Put the mouse on the 'Contacts' and click on 'Create Contact'
* Fill the blanks
* With the blanks filled, Click on 'Save'
* After saving the contact, go to the 'View Contacts' section
* Mark the created contact and where it says 'Bulk Action' you click and select Export

## Expected Result:
* SuiteCRM should download a csv
* The csv file should contain all the contact information.

## Actual Result:
* The file is downloaded
* Contain all the required information

## Result Analysis:
Exportation on SuiteCRM is working pretty good doing what is expected to do.

## Error Description (if applicable):
No errors in system behavior.

## Evidence:
* File being downloaded correctly.  
![csvFile](/images/testCase08/csvFile.png)