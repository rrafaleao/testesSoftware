# Access to Restricted Features
## Description: 
Test if only a admin user can see the admin panel.

## Objective:
Test access permissions, checking whether users with different profiles (Admin and User) see the corresponding options.

## Prerequisites:
* A valid user account exists in the system.
* A valid admin account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* See if there's a admin panel.

## Expected Result:
* If the user is not a admin should not appear a admin panel for him.
* If he's a admin, the admin panel needs to appear.
* Should appear a message saying that the user isn't a admin

## Actual Result:
The user that isn't a admin don't have acess to the admin panel and the admin have. If user's try to open the admin panel url being with a normal role appears a error mensage.

## Error Description (if applicable):
No errors in system behavior.

## Evidence:
![Sucessful test](/images/testCase10/sucessfulTest.png)