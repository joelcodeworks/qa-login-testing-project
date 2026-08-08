# QA Login Testing Project
## Project Summary
This project brings together test cases, bug documentation, basic Jira usage and structured information with the aim of representing a practical example of initial QA work.
## Project Scope
This project aims to simulate a basic functional testing process for a login functionality. It includes test case definition, test data, bug documentation and issue tracking using tools commonly used by QA professionals.
## Objective
To design and document test cases for the login functionality of an application, applying basic QA concepts such as positive and negative test cases, test data and result documentation.
## Functionality Under Test
The functionality under test is the login feature of a web application. The project focuses on validating successful login attempts with valid credentials and verifying how the system handles incorrect or incomplete login data
## Tools Used
- **Notion:** Project documentation and organization.
- **Jira:** Task and bug tracking.
- **GitHub:** Project repository and public documentation.
## Project Structure
## Included Documentation
## Working Methodology
## Applied Best Practices
## Test Cases
### Positive Test Cases
#### Test Case 1: Login with valid credentials
**Description:** Verify that a registered user can log in successfully by entering a valid username and password.


**Expected result:** The system successfully authenticates the user after valid credentials are entered and redirects the user to the application's main page without displaying any error messages.

#### Test Case 2: Login with valid credentials using the Enter key
**Description:** Verify that the user can log in successfully by pressing the Enter key after entering valid credentials, without having to click the Login button.


**Expected result:** The system successfully authenticates the user when the Enter key is pressed after valid credentials are entered and redirects the user to the main page without displaying any errors.

### Negative Test Cases
#### Test Case 1: Login with an incorrect password
**Description:** Verify that the system prevents access when a registered user enters an incorrect password and displays an appropriate error message.


**Expected result:** The system prevents access when an incorrect password is entered and displays a clear error message without allowing the user to log in.

#### Test Case 2: Login with an empty password field
**Description:** Verify that the system does not allow the user to log in when a valid username is entered but the password field is left empty, and displays an appropriate validation message.


**Expected Result:** The system prevents the login attempt when the password field is empty and displays an appropriate validation message.

## Test Data
| Test Case | Username | Password | Expected Result |
| --- | --- | --- | --- |
| Positive 1 | valid_user | valid_password | Successful login |
| Positive 2 | valid_user | valid_password | Successful login using the Enter key |
| Negative 1 | valid_user | incorrect_password | Error message displayed |
| Negative 2 | valid_user | (empty) | Validation message displayed |
## Expected Results
Each test case defines the expected behavior of the application when the test is executed. The expected results are used to compare the actual outcome with the expected behavior and determine whether the test has passed or failed.
## Bug Reports
### Bug 001
**Title:** Login does not respond when pressing the Enter key

**Related to:** Positive Test Case 2

**Steps to Reproduce:**
1. Open the login page
   
2. Enter a valid username
   
3. Enter a valid password
   
4. Press the Enter key
   
5. Observe the application's behavior

**Expected Result:** The application should log in successfully when the Enter key is pressed after valid credentials have been entered, redirecting the user to the main page without requiring a click on the Login button.

**Actual Result:** The application does not log in when the Enter key is pressed. The user remains on the login page and must manually click the Login button to access the application.

**Severity:** High

**Priority:** High

**Priority Justification:** High priority is assigned because the issue affects one of the application's core functionalities(user login), although a temporary workaround is available by clicking the Login button.

**Conclusions:**

**Project Status:** Two positive test cases and two negative test cases have been defined.

**Notes:** This bug affects the user experience because a common action, such as pressing the Enter key to submit a form, does not work as expected. Although an alternative exists (clicking the Login button),the behavior is not consistent with the expected functionality.

**Impact:** This issue affects one of the application's essential functionalities, making access more difficult for users who commonly use the Enter key to submit forms. Although the Login button provides a functional workaround, the overall user experience is negatively affected.

**Follow-up Status:** Pending review and correction by the development team.

### Bug 002
## Demonstrated Skills
## Target Audience
## Learning Outcomes
## Lessons Learned
## Project Value
## Possible Future Improvements
## General Conclusion
