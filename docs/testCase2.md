# Login with Incorrect Credentials  
## Description: 
This test verifies that the SuiteCRM login process works correctly when invalid credentials are provided.

## Objective:
To confirm that the system authenticates a user with valid credentials and doesn't let users with wrong username or password log in.

## What is being tested:
The login functionality and flow of the SuiteCRM system.

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an invalid username ("usuarioerrado") and password ("senhaerrada").
* Click the "Log in" button.
* Observe the system's response.
* Try again with a valid username but incorrect password.
* Click the "Login" button.
* Observe the system's response.

## Expected Result:
* When invalid credentials are provided, the system should not allow access to the dashboard.
* The system should display an appropriate error message indicating that the login attempt failed.
* The error message should provide adequate information without revealing sensitive details about the account.
* The login page should be displayed again, allowing the user to retry.

## Actual Result:
* When invalid credentials were entered, the system displayed the error message: "Login credentials incorrect, please try again."
* The system remained on the login page and did not grant access to the dashboard.

## Result Analysis:
The system behaved as expected by properly identifying invalid credentials and preventing unauthorized access. The error message was clear and informative without revealing which specific credential (username or password) was incorrect, which is a security best practice.

## Error Description (if applicable):
No errors in system behavior. The authentication system functioned as designed.

## Evidence:
Screenshot of the login page showing the "Login credentials incorrect, please try again." error message.  


![LoginIncorreto](/images/testCase2/invalidLogin.png)