
# CampusConnect - Use Case Diagram

## Actors
- Student
- Faculty
- Admin

## Use Case Diagram

```mermaid
flowchart LR
    Student([Student])
    Faculty([Faculty])
    Admin([Admin])

    subgraph CampusConnect System
        A((Login))
        B((View Courses))
        C((View Assignments))
        D((Submit Assignment))
        E((View Submission Status))
        F((Manage Assignments))
        G((Review Submissions))
        H((Provide Feedback))
        I((Manage Users))
        J((Manage Courses))
        K((View Announcements))
    end

    Student --- A
    Student --- B
    Student --- C
    Student --- D
    Student --- E
    Student --- K

    Faculty --- A
    Faculty --- F
    Faculty --- G
    Faculty --- H
    Faculty --- K

    Admin --- A
    Admin --- I
    Admin --- J
```

## Description

The use-case diagram represents the interactions between three main actors and the CampusConnect system.

- Student: Views courses, checks assignments, submits work and tracks submission status.
- Faculty: Creates assignments, reviews submissions and provides feedback.
- Admin: Manages user accounts and course information.
