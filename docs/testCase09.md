# Interface Responsivity
## Description: 
Tests the responsiveness of different devices

## Objective:
Evaluate the adaptation of the interface to different screen sizes (desktop, tablet, smartphone).

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
* A DevTools with devices test option on browser

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.

## Expected Result:
* Be able to use all SuiteCRM features
* Have a resposivy interface 

## Actual Result:
| Device            | Screen Size Simulation | Interface Loaded Correctly | All Features Functional | Layout Responsive |
|-------------------|------------------------|-----------------------------|--------------------------|--------------------|
| iPhone SE (iOS 12) | Smartphone             | ✅                          | ✅                       | ✅                 |
| iPad Pro          | Tablet                 | ✅                          | ✅                       | ✅                 |
| Samsung A51/71    | Smartphone (Android)   | ✅                          | ✅                       | ✅                 |

## Result Analysis:
The system demonstrated excellent responsiveness across all tested devices. All elements adjusted correctly to the screen size, maintaining usability and functionality. No visual or functional issues were detected during the tests.

## Evidence:

![Iphone SE](/images/testCase09/iphoneTest.png)

![IPad Pro](/images/testCase09/ipadTest.png)

![Samsung A51/71](/images/testCase09/samsungTest.png)
