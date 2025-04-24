# Data Import

## Description
Test the functionality of importing data into the system from a CSV file.

## Objective
To verify that the system correctly imports data from a CSV file.

## Prerequisites
- A valid user account exists in the system.
- Access to the SuiteCRM instance at crm.alunostds.dev.br.
- A valid CSV file formatted according to the system's import template.

## Test Procedure
* Go to the 'Import contacts' section.
* Download the model given by the SuiteCRM software.
* Change the model.
* Put the csv file on it and import.

## Expected Result
* The model given by them needs to be with the correct information.
* SuiteCRM needs to create a contact based on the informations given by the csv file.


## Actual Result
* The given model is actually wrong, and does not give all the information needed.

## Result Analysis
It is not possible to create a contact by the data import function,

## Error Description
* The given model is wrong and is not possible to import data to SuiteCRM

## Evidence
![importError](/images/testCase07/importError.png)

