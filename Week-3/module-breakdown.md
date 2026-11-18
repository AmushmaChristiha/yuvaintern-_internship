# CampusConnect – Module Breakdown

## 1. Introduction

CampusConnect is planned as a student course and assignment management system. The application will be divided into independent modules, with each module responsible for a specific function.

## 2. Main Modules

### 2.1 User Authentication Module
- Register new users.
- Allow existing users to log in.
- Validate user credentials.
- Manage user sessions and access permissions.

### 2.2 Student Management Module
- Maintain student profile information.
- Display enrolled courses.
- Allow students to view their academic activities.

### 2.3 Course Management Module
- Create and manage courses.
- Display available course details.
- Handle student course enrollment.

### 2.4 Assignment Management Module
- Create and publish assignments.
- Display assignment descriptions and deadlines.
- Allow students to submit their work.
- Track submission status.

### 2.5 Notification Module
- Notify students about new assignments.
- Provide deadline reminders.
- Display important course updates.

## 3. Module Interaction

1. The user logs in through the Authentication Module.
2. The system verifies the user's credentials.
3. The Student Management Module displays the student's dashboard.
4. The Course Management Module provides course information.
5. The Assignment Management Module manages assignment details and submissions.
6. The Notification Module provides relevant updates and reminders.

## 4. Proposed Backend Components

| Component | Responsibility |
|---|---|
| UserController | Handles user-related requests |
| CourseController | Manages course operations |
| AssignmentController | Handles assignment operations |
| User Model | Stores user information |
| Course Model | Stores course information |
| Assignment Model | Stores assignment information |
| Auth Middleware | Protects restricted routes |

## 5. Conclusion

The modular design separates responsibilities and makes the proposed system easier to develop, test, and maintain. Each module can be developed and improved independently while communicating through defined interfaces and REST APIs.
