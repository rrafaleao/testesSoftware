# Task Assignment
## Description: 
Test if is possible to assigning a task to somebody on SuiteCRM software.

## Objective: 
Test the functionality of assigning tasks to specific users and checking the corresponding notification.

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
* A valid contact to assigment the task to him

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Go to the 'task' section, on the topbar.
* Create a task assigment to a contact
* See if in the contact section is possible to see the assigmented task

## Expected Result:
* The task needs to be created and be visible on the task section.
* The task needs to be seen on the assigment contact.

## Actual Result:
* Task is created correctly.
* It is possible to see it on the assigment contact.

## Result Analysis:
The task assigment function on SuiteCRM is working perfectualy fine, with no errors.

## Error Description (if applicable):
No errors in system behavior.

## Evidence:
* Task being seen on the assigment contact.
![assigmentTask](/images/testCase15/assigmentTask.png)
