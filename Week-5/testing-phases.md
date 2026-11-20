# CampusConnect – Testing Phases

## 1. Unit Testing
Unit testing verifies individual functions, components, and modules independently.

Examples:
- Validate student login input.
- Check assignment deadline calculations.
- Test functions that count pending assignments.

Recommended tools: Jest, Vitest, React Testing Library.

## 2. Integration Testing
Integration testing checks whether different modules communicate correctly.

Examples:
- Verify frontend API communication.
- Check assignment submission and database storage.
- Test authentication middleware with protected routes.

Recommended tool: Supertest.

## 3. System Testing
System testing validates the complete application as an integrated system.

Examples:
- Student login and dashboard navigation.
- Course selection and assignment viewing.
- Assignment submission and status updates.

Recommended tools: Playwright, Selenium.

## 4. User Acceptance Testing (UAT)
UAT checks whether the application meets actual user requirements.

Examples:
- Students check whether they can submit assignments easily.
- Administrators verify course and assignment publishing.
- Users provide feedback about navigation and usability.

## 5. Testing Completion Criteria

- Critical test cases should pass.
- High-severity defects should be resolved or formally accepted.
- Regression testing should be completed.
- Test results should be documented.

## Conclusion
These testing phases provide a structured approach to validating CampusConnect at different levels before deployment.
