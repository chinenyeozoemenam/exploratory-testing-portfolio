# GMAIL LOGIN TEST PLAN

## 1. Project Introduction

This project focuses on testing the login functionality of Gmail to ensure that users can securely and successfully access their email accounts.

The testing will cover different login scenarios, including successful login, incorrect passwords, empty fields, password recovery, and other possible user interactions.

## 2. Testing Objectives

The objectives of this testing project are to:

- Verify that users can log in with valid email addresses and passwords.
- Confirm that incorrect login details are rejected.
- Check that required fields cannot be left empty without appropriate feedback.
- Verify that the password recovery process works as expected.
- Identify and report any defects found during testing.
## 3. Scope of Testing

This testing will focus on checking the Gmail login process and how the system responds to different user inputs.

**The testing will cover:**

- Successful login with a valid email address and password.
- Login attempts with incorrect passwords.
- Login attempts with empty email or password fields.
- Testing special characters and long text inputs.
- Checking how the login page handles SQL injection attempts.
- Testing the password recovery process.
- Checking the Remember Me functionality, where available.
- Testing login access across different devices.

**Out of Scope:**

- Testing Gmail email-sending and receiving features.
## 4. Testing Approach

The Gmail login page will be tested manually using different test scenarios to check whether it works as expected.

The following testing methods will be used:

- **Positive Testing:** Checking that users can log in with correct details.
- **Negative Testing:** Checking how the system responds to incorrect login details.
- **Boundary Testing:** Checking how the system handles very long or unusual inputs.
- **Security Testing:** Checking how the login page responds to suspicious inputs, including SQL injection attempts.
- **Cross-Device Testing:** Checking the login process on different devices.

Test cases will be prepared and executed. The actual results will be compared with the expected results, and any defects found will be documented.
## 5. Test Environment and Tools

**Test Environment:**
- A computer or laptop with internet access.
- Google Chrome web browser.
- Gmail login page.

**Testing Tools:**

- **Google Chrome:** Used to access and test the Gmail login page.
- **Microsoft Excel:** Used to create, organize, and document test cases and testing results.

All testing activities were performed manually using the tools listed above.

## 6. Test Schedule

The testing activities will be carried out in the following stages:

| Activity | Description |
|---|---|
| Test Planning | Understanding the Gmail login requirements and preparing the test plan. |
| Test Case Design | Writing and organizing the test cases in Microsoft Excel. |
| Test Execution | Performing the test cases using Google Chrome. |
| Result Documentation | Recording actual results and comparing them with expected results. |
| Test Reporting | Documenting failed test cases and reporting any issues found. |

The testing schedule will depend on the availability of the test environment and completion of each testing activity.

## 7. Roles and Responsibilities

The testing activities will be carried out by the QA tester.

The responsibilities include:

- Reviewing the Gmail login requirements.
- Preparing and organizing test cases.
- Executing test cases manually using Google Chrome.
- Recording actual test results in Microsoft Excel.
- Comparing actual results with expected results.
- Identifying and documenting any issues found during testing.
- Preparing a summary of the testing activities and results.

- ## 8. Entry and Exit Criteria

**Entry Criteria:**

Testing can begin when:
- The Gmail login page is accessible.
- Google Chrome is available and working.
- Test cases have been prepared.
- Internet connection is available.

**Exit Criteria:**

Testing can be considered complete when:
- All planned test cases have been executed.
- Test results have been recorded in Microsoft Excel.
- Failed test cases have been documented.
- A summary of the testing results has been prepared.

- ## 9. Risks and Mitigation

The following risks may affect the testing activities:

| Risk | Mitigation |
|---|---|
| Poor internet connection | Ensure a stable internet connection before testing. |
| Gmail login page is unavailable | Retry testing when the page becomes accessible. |
| Test account access issues | Ensure the test account is available before testing. |
| Browser-related issues | Use an updated version of Google Chrome. |
| Unexpected changes to the login page | Review and adjust test cases when necessary. |

## 10. Test Plan Approval

This test plan serves as a guide for carrying out the Gmail login testing activities.

The testing activities will be conducted based on the objectives, scope, approach, and criteria outlined in this document.

**Prepared By:** QA Tester

**Project:** Gmail Login Testing

**Status:** Completed
- Testing Google Drive and other Google services.
- Testing features unrelated to the login process.
