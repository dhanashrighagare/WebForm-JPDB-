# WebFormUsingJPDB
Web Form which stores the Employee data through the web page in an EMP-REL table in EMPLOYEE database through Save button.

## Benefits of using JsonPowerDB
Simple to use
Real-time Database
Reduced development and maintainance cost
Maximum data processing performance

## Release History
7th August 2022

## Illustrations
Enter the data into the Web Form (Emp id, Emp name, Emp email)

Click the save button

On-click <br/>
  Validate the data <br/>
  Creating PUT request <br/>
  Executing the request <br/>
  Reset the data <br/>

Check the results on http://api.login2explore.com:5577/user/jpdb_view.html

## Scope of functionalities
saveEmployee(): On-click of save button <br/>
validateAndGetFormData(): Validates the data <br/>
createPUTRequest() and executeCommandAtGivenBaseUrl(): For request creation and execution (Taken from "http://login2explore.com/jpdb/resources/js/0.0.3/jpdb-commons.js") <br/>
resetForm(): resets form for the new data entry <br/>

## Examples of use
Backend database in dynamic web application/ Mobile/ Desktop Apps 

## Project status
Completed the linking of JPDB to the Web Form. <br/>
Performed all the functionalities. 

## Sources
Introduction to JsonPowerDB: https://learn.login2explore.com/course/view.php?id=7
