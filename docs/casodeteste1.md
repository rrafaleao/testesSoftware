# Valid Login with Correct Credentials  
## Description: 
This test verifies that the SuiteCRM login process works correctly when valid credentials are provided.
## Objective:
To confirm that the system authenticates a user with valid credentials and redirects to the dashboard properly.
## What is being tested:
 The login functionality and authentication flow of the SuiteCRM system.
## Prerequisites:
* A valid user account exists in the system.

* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).

## Test Procedure:


* Navigate to crm.alunostds.dev.br.

* Enter the username "admin" and password "admin123".

* Click the "Login" button.

* Observe the redirection to the main dashboard.

## Expected Result:

* The system successfully authenticates the user and redirects to the dashboard, displaying relevant user information and modules.

## Actual Result:

| Test Case                | Entry       | Actual Result          | Status |
|------------------------------|---------------|--------------------------|--------|
| Valid Password & valid username | "usuario123", "usuario"  | True                     | ✅     |
| Uppercase Password          | "USUARIO123"    | False                    | ✅     |
| Short password                  | "usua12"       | False                    | ✅     |
| Empty password                  | ""            | False                    | ✅    |
| Invalid Password & Valid Username | "usuar123", "usuario"| False                    | ✅     |
| Valid Password & Invalid Username | "usuario123", "user" | False                    | ✅     |



## Result Analysis:

If the user is logged in as an admin user, no errors occur.


When logging in as a standard user, the browser indicates that data is being leaked.

## Error Description (if applicable):

![vazamento de dados](/images/image.png)

Data leak error probably occurring because the password is not hashing when it is sent to the database.

the error only occurs if the user logs in with a standard user

## Evidence:

Screenshot of the login page with entered credentials.

* System specifications: Windows 11, Chrome Version 135.0.7049.85, Screen Resolution 1920x1080.
