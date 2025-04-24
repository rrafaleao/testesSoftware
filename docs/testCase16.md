# Notification Generation
## Description: 
Test made by the purpose to see if the software generates and send the notifications 

## Objective:
To confirm that the system generates appropriate notifications in response to specific actions (e.g., record creation or update).

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Create a contact
* See if the notification on the dashboard is created

## Expected Result:
* Notification needs to appear in the dashboard
* It needs to be possible to delete and to Reply the notification.

## Actual Result:
* Notification appear on the dashboard.
* It is possible to delete a notification
* It is possible to reply a notification
* If you click reply more than once, the bar will get bigger and bigger, which shouldn't happen.

## Result Analysis:
The functionalitys are working good, but needs some repair.

## Error Description (if applicable):
Every time that you click on the button 'reply' the bar the reply goes lower.

## Evidence:

* Error demostration  
![errorNotification](/images/testCase16/errorNotification.png)  

* All the notifications being receive correctly  
![notificationTest](/images/testCase16/notificationTest.png)  