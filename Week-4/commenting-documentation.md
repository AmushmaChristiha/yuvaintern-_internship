# CampusConnect – Commenting and Documentation Strategy

## 1. Introduction

Inline documentation helps developers understand the purpose, logic, and expected behavior of code. Proper comments make software easier to maintain, debug, and improve.

## 2. Commenting Guidelines

- Write comments for complex or non-obvious logic.
- Explain why a particular approach is used.
- Avoid comments that simply repeat the code.
- Keep comments short, clear, and meaningful.
- Update comments whenever the related code changes.
- Document important assumptions and edge cases.

## 3. Inline Comment Example

```javascript
// Remove extra spaces before validating the assignment title.
const cleanTitle = title.trim();

if (cleanTitle.length === 0) {
  return "Assignment title is required";
}
```

The comment explains why trimming is necessary before validation.

## 4. JSDoc Documentation

JSDoc is used to document JavaScript functions, parameters, and return values.

```javascript
/**
 * Checks whether a student can submit an assignment.
 *
 * @param {string} dueDate - Assignment deadline.
 * @returns {boolean} Whether submission is allowed.
 */
function canSubmitAssignment(dueDate) {
  return new Date(dueDate) >= new Date();
}
```

## 5. Javadoc

Javadoc is commonly used to document Java classes and methods.

```java
/**
 * Calculates the number of pending assignments.
 *
 * @param assignments List of student assignments.
 * @return Number of assignments not submitted.
 */
public int countPending(List<Assignment> assignments) {
    // Implementation
}
```

## 6. Python Docstrings

Python docstrings explain the purpose and usage of functions and classes.

```python
def calculate_total(marks):
    """Calculate the total of the given marks.

    Args:
        marks: List of student marks.

    Returns:
        Sum of all marks.
    """
    return sum(marks)
```

## 7. Documentation Best Practices

- Use JSDoc for important JavaScript functions and modules.
- Document parameters and return values.
- Explain exceptions and side effects when applicable.
- Maintain accurate documentation.
- Use consistent documentation formats.

## 8. Conclusion

A consistent commenting and documentation strategy improves code understanding and supports future maintenance. These practices will be followed during the planned CampusConnect implementation.
