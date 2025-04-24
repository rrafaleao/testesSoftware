# Data Query Performance

## Description
Test the software support to a large volume of data.

## Objective
Measure system response time when performing queries on large volumes of data, comparing it with the expected time.

## Prerequisites
- A valid user account exists in the system.
- Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).

## Test Procedure
1. Logged into the system with a valid user account.
2. Accessed the "Leads" module.
3. Used the advanced search to filter leads created.
4. Clicked "Search" and measured the response time.

## Expected Result
The query should return results within 5 seconds.

## Actual Result
Query returned results in 3 seconds.

## Error Description
No errors in system behavior

## Evidence

![searchLead](/images/testCase11/searchLead.png)