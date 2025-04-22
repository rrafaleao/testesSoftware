# Email Integration
## Description: 
Test if the software send a email to the required people.

## Objective:
Test the email notification sending functionality, confirming that emails are sent and received correctly.

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
* An valid Email to receive the message.

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Click on 'Compose' on the Email button. 
* Fill the blanks.
* Click on Send Email.

## Expected Result:
* Be possible to send a email
* The email needs to be send to the people that you told'em to send 

## Actual Result:
* Is not possible to fill the blank 'From'
* It's not possible to send the email without a sender 

## Error Description (if applicable):
The blank 'from' doesn't receive any type of data, and there's no way to send the Email without filling that blank.

## Evidence:
* Blank that is not possible to fill  
![alt text](/images/testCase12/unfilledBlank.png)  

* Error if you try to send the Email without filling that blank  
![alt text](/images/testCase12/sendingEmailError.png)  