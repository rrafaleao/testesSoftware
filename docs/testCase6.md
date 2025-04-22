# Records Search
## Description: 
Tests the software's filtering ability

## Objective:
Validate the search engine, using different criteria (name, email, etc.) to ensure the accuracy of the results.

## Prerequisites:
* A valid user account exists in the system.
* Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
* A Created Contact

## Test Procedure:
* Navigate to crm.alunostds.dev.br.
* Enter an valid username and password.
* Click the "Log in" button.
* Put the mouse on the 'Contacts' and click on 'Create Contact'
* Fill the blanks
* With the blanks filled, Click on 'Save'
* Go on the 'View contacts' Section. 
* Click on Filter

## Expected Result:
* All filter gaps are working
* Be able to save filters, which need to work correctly
* Software needs to filter even if it's in uppercase or lowercase

## Actual Result:
* All filter blanks are working perfectly.
* User's able to save his own filters.
* SuiteCRM filter is working perfectualy with lowercase and uppercase.

## Result Analysis:
Filter section on SuiteCRM is working perfectualy, user can save his own filters, can filter with lower and uppercase and find his expected results.

## Error Description (if applicable):
No errors in system behavior.

## Evidence:

![Saved Filters](/images/testCase6/savedFilters.png)
* Filtro salvo que funciona perfeitamente para filtros que precisam ser rápidos.

![Filter Test](/images/testCase6/filterTest.png)
* Resultado de uma busca no filtro 'nome' Por 'TESTE' tudo em maiusculo para testar as capacidades de diferencia-las.