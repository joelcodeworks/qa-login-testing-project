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
The project is organized into sections covering the project objective, test cases, test data, bug documentation, and task tracking through Jira, providing clear navigation and organized review of the project content.

## Included Documentation
This project includes positive and negative test cases, examples of documented bugs, basic task tracking in Jira, and a structure prepared for presentation as part of a professional QA portfolio.

## Working Methodology
The project was developed incrementally, with each stage documented and the structure reviewed periodically to maintain consistency and support future improvements.

## Applied Best Practices
Throughout the project, a consistent structure, organized documentation, and continuous content review were maintained to improve clarity and facilitate understanding.

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

**Title:** Unclear error message when entering an incorrect password

**Related to:** Negative Test Case 1

**Steps to Reproduce:**
1. Open the login page.
2. Enter a valid username.
3. Enter an incorrect password.
4. Click the Login button.
5. Observe the displayed message.

**Expected Result:** The application should display a clear and informative error message indicating that the password is incorrect, allowing the user to correct the entered data.

**Actual Result:** The application displays a generic error message when an incorrect password is entered. The message does not clearly indicate what the problem is or provide guidance to the user on how to correct it.

**Severity:** Medium

**Priority:** Medium

**Priority Justification:** Medium priority is assigned because the core functionality remains operational, but the quality of the user experience is affected by the lack of clarity in the displayed message.

**Status**:To Do

**Conclusions:**

**Project Status:** Two positive test cases and two negative test cases have been defined.

**Notes:** This issue is related to the quality of communication with the user rather than a functional failure of the authentication process.

**Impact:** This issue primarily affects the user experience, as an unclear error message can cause confusion and make it more difficult for the user to understand why they were unable to log in.

**Follow-up Status:** Pending review and improvement by the development team to provide clearer and more useful error messages to the user.

## Demonstrated Skills
This project demonstrates basic skills in test case design, bug documentation, evidence organization, task tracking, and the use of tools commonly used by QA professionals.

## Target Audience
## Learning Outcomes
This project provided practical experience in organizing tests, documenting bugs, using basic project management tools, and preparing evidence for a professional QA portfolio. It also reinforced the importance of clear documentation, consistent organization, and continuous review to improve the quality and clarity of the work.

## Project Evidence

Note: The screenshots below provide visual evidence of the work carried out in Jira. The Jira interface, bug descriptions, comments and activity history are shown in their original language, while the project documentation in this repository has been prepared in English for portfolio presentation.

### Project Board
The Jira project board showing the main project task and the current status of the project activities.

![Project Board](evidence/Project%20Board%201.png)

Additional Jira project board evidence showing the organization and tracking of the project activities.

![Project Board](evidence/Project%20Board%202.png)

### Main Task
The main Jira task containing the project information, objectives and work being carried out.

![Main Task](evidence/Main%20Task.png)

### Bug 001
Jira evidence for Bug 001, showing the bug description, reproduction steps, expected result, actual result, severity, priority and follow-up status.

![Bug 001](evidence/Bug%20001.png)

### Bug 002
Jira evidence for Bug 002, showing the bug description, reproduction steps, expected result, actual result, severity, priority and follow-up status.

![Bug 002](evidence/Bug%20002.png)

### Bugs Overview
Jira overview showing the documented bugs and their organization within the project.

![Bugs Overview](evidence/Bugs%20Overview.png)

Additional Jira overview evidence showing the documented bug information and project tracking details.

![Bugs Overview](evidence/Bugs%20Overview%202.png)

Additional Jira evidence showing the available bug information and the organization of the documented issues.

![Bugs Overview](evidence/Bugs%20Overview%203.png)
 
## Lessons Learned
## Project Value
## Possible Future Improvements
## General Conclusion
