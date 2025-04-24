# Creating a New Contact
## Description: 
This test checks the creation of a new contact

## Objective:
Ensure that the contacts module allows the creation of a new contact with all the necessary information.

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Put the mouse on the 'Contacts' and click on 'Create Contact'
* Fill the blanks
* With the blanks filled, Click on 'Save'

## Expected Result:
* When email or phone is invalid, it may not be possible to create a contact.
* The system should display an appropriate error message indicating which field was not filled in.
* User cannot create a contact without filling in key information (First Name, Last Name, Email, Phone)

## Actual Result:
* User can create a contact with just the 'Last Name' filled in. 
* Email needs to have an extension to be valid
* Phone needs to be a number to be valid 

## Result Analysis:
The system did not behave ideally, it is possible to create a contact with only the surname, which should not be possible. Otherwise, the program flowed well, being possible to view the created contacts, the email and telephone columns accepting only valid data.

## Error Description (if applicable):
When the user try to create a empty contact, the only required field is 'Last name'  
And if user put anything there, it become possible to create a contact only with last name

## Evidence:
![descricaoErro](/images/testCase3/missingBlanks.png)  
