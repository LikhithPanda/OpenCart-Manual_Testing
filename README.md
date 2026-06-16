# **Manual Testing OpenCart WebApp**

This project is dedicated to manual testing of the OpenCart web application. It includes test cases, test plans, and documentation to guide manual testers in evaluating the functionality and usability of OpenCart.

## **Features:**

1. A comprehensive set of manual test cases.
2. Test plans and documentation for organized testing.
3. Instructions for performing manual tests on OpenCart.



# **Test Environment:**

XAMPP Control Panel -- for running Apache Server \& MySQL at once

&#x09;(MySQL port numbers in MySQL config \& in XAMPP config files must me same, or else you will get error while running MySQL server)



## **Getting Started:**

1. Download the OpenCart web application from [LINK](https://www.opencart.com/index.php?route=cms/download).
2. Download the XAMPP from the browser (msi file).
3. Extract the XAMPP msi file (control panel)
4. Extract the downloaded zip file of OpenCart \& place the extracted zip file at C:\\xampp\\htdocs
5. The extracted file contains all the files related to OpenCart.
6. Rename the OpenCart i.e., remove the version number in the directory name
7. Also, rename config files at C:\\xampp\\htdocs\\opencart\\upload\\config-dist.php to C:\\xampp\\htdocs\\opencart\\upload\\config.php \& C:\\xampp\\htdocs\\opencart\\upload\\admin\\config-dist.php to C:\\xampp\\htdocs\\opencart\\upload\\admin\\config.php
8. Run the Apache server \& MySQL server from XAMPP Control Panel
9. In the browser, open localhost/phpMyAdmin. This will take you to the database, create a new database by clicking New icon at the top left side of the screen, name the database.
10. In another window of browser, open localhost/opencart/ you'll get the file structure (it wont appear again after completion of installation), Click on Continue at Licence Agreement page.
11. It'll take you to Pre-Installation page where all the required extension are installed make sure all are installed or else find the error and solve it using LLMs \& continue on Continue.
12. At the Configuration page, give the database details \& click on Continue.
13. After completion, delete the install folder C:\\xampp\\htdocs\\opencart\\upload .
14. Read the FRS document and prepare and understand Test Plan \& Test Scenarios.
15. Review the provided Test Plan, Test Scenarios \& Test Cases.
16. Execute the  Test Cases and find bugs if there and report them.



## **Project Structure:**

|**File Name**|**Description**|
|-|-|
|OpenCart-1-FRS.pdf|This PDF contains the Functional Requirements Specification (FRS) document for OpenCart, outlining the functional and non-functional requirements of the software, acquired from GitHub repository of Ganga Pandey|
|OpenCart-2-TestPlan.pdf|This PDF is a Test Plan document for OpenCart, providing an overview of the testing strategy, objectives, scope, and schedule for testing the software.|
|OpenCart-3-TestScenarios.xlsx|This Excel file contains test scenarios for OpenCart, which describe various situations and conditions that need to be tested to ensure the software functions correctly.|
|OpenCart-4-TestCases.xlsx|This Excel file contains a set of test cases specifically related to web registration functionality in OpenCart. It likely includes detailed steps, expected results, and test data.|
|OpenCart-5-TestExecution.xlsx|This Excel file contains a set of test executions specifically related to web registration functionality in OpenCart. It likely includes detailed steps, test data, expected results, actual results, priority, test results, and comments.|
|OpenCart-6-BugReportBugReport.xlsx|This Excel file is used for tracking and documenting software bugs and issues found during testing. It may include details such as bug descriptions, severity, status, and steps to reproduce.|
|OpenCart-7-RTM.xlsx|This Excel file contains the Requirement Traceability Matrix document related to web registration functionality in OpenCart. It likely includes requirement ID, requirement description, test scenario ID and description, test cases, test result, defect ID, and also the summary report.|



# **Report:**

Total Test Cases: 504

Total Test Cases Executed: 256

Total Passed Cases: 194

Total Failed Cases: 20

Total Blocked Cases: 42

Pass Rate: 75.78%



Defect Summary:-

Minor: 11

Major: 6

Crucial: 2

Critical: 1



