# CampusConnect – Coding Standards

## 1. Naming Conventions

| Element | Convention | Example |
|---|---|---|
| Variables | camelCase | studentName |
| Functions | camelCase | calculateDeadline() |
| React Components | PascalCase | AssignmentCard |
| Classes | PascalCase | AssignmentService |
| Constants | UPPER_SNAKE_CASE | MAX_FILE_SIZE |
| Boolean variables | is/has/can prefix | isSubmitted |

## 2. Code Formatting Rules

- Use two spaces for indentation in JavaScript.
- Use consistent quotation marks and semicolons.
- Keep lines around 100 characters where practical.
- Add spaces around operators and after commas.
- Use meaningful variable and function names.
- Avoid unnecessary nested conditions.
- Remove unused variables and debugging statements.

## 3. File Organization

Organize files according to their responsibilities.

### Frontend
- components – Reusable UI components.
- pages – Application screens.
- services – API communication.
- hooks – Reusable React hooks.
- utils – Helper functions.

### Backend
- controllers – Handle incoming requests.
- models – Define database structures.
- routes – Define API endpoints.
- middleware – Authentication and validation.
- config – Application configuration.
- services – Business logic.

## 4. General Guidelines

- Keep functions focused on one responsibility.
- Avoid unnecessary code duplication.
- Follow consistent formatting throughout the project.
- Use comments for complex or non-obvious logic.
- Review code before committing changes.

## 5. Conclusion

These coding standards provide a common structure for CampusConnect development. Following them will improve readability, consistency, and maintainability.
