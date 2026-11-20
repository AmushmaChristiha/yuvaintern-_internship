# CampusConnect – Test Cases

## 1. Introduction

Test cases define the steps, inputs, and expected results used to verify application functionality.

## 2. Functional Test Cases

| Test ID | Test Scenario | Expected Result | Priority |
|---|---|---|---|
| TC-01 | Login with valid credentials | Student dashboard opens | High |
| TC-02 | Login with incorrect password | Error message is displayed | High |
| TC-03 | View enrolled courses | Course details are displayed | Medium |
| TC-04 | Submit assignment before deadline | Submission is saved successfully | High |
| TC-05 | Submit assignment after deadline | Submission is rejected | High |
| TC-06 | Access invalid course ID | Appropriate error is returned | Medium |

## 3. Detailed Test Case – Student Login

**Test ID:** TC-01

**Objective:** Verify student login functionality.

**Preconditions:**
- Student account exists.
- Application is accessible.

**Test Steps:**
1. Open the login page.
2. Enter valid student credentials.
3. Click the Login button.

**Expected Result:**
The system authenticates the student and redirects them to the dashboard.

## 4. Detailed Test Case – Assignment Submission

**Test ID:** TC-04

**Objective:** Verify assignment submission before the deadline.

**Preconditions:**
- Student is logged in.
- Student is enrolled in the course.
- Assignment is open for submission.

**Test Steps:**
1. Open the course.
2. Select the assignment.
3. Attach or enter the required work.
4. Click Submit.

**Expected Result:**
The system saves the submission and displays a confirmation message.

## 5. Test Result Recording

Each test execution should record:
- Test ID
- Execution date
- Actual result
- Pass or Fail status
- Defect details, if applicable

## 6. Conclusion

These test cases provide a practical foundation for checking the major CampusConnect features and identifying functional defects.
