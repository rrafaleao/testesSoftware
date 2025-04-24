# Exporting Reports
## Description:  
Test if the functionality of export the data to PDF is working good.

## Objective:  
Ensure that generated reports can be exported to common formats such as PDF or Excel, while maintaining data integrity.

## Prerequisites:  
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
* A created Report to export to PDF.

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Put the mouse on 'More' in the topbar.
* Look for 'reports' and click on it.
* Then, go to create reports.
* Fill the blanks and click on save.
* Click on actions.
* Then click on 'Download PDF'.


## Expected Result:  
* SuiteCRM needs to create a PDF with all the informations of the report.

## Actual Result:  
* It is created a PDF with all the information that contains on the report

## Result Analysis:  
SuiteCRM do what is supposed to and create a PDF with the reports. But, it is not possible to export to Excel.

## Error Description (if applicable):  
No errors in system behavior

## Evidence: 

* Where is the button to the export to pdf  
![download Pdf](/images/testCase18/downloadPdf.png)  
* File that is downloaded when you export to Pdf  
![pdf File](/images/testCase18/pdfFile.png)  


