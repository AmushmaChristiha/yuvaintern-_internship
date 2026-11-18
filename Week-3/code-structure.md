# CampusConnect – Code Structure

## 1. Overview
CampusConnect follows a modular three-tier architecture. The frontend, backend, and database are organized separately to improve maintainability and scalability.

## 2. Frontend Structure

```text
frontend/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── hooks/
│   ├── context/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
├── package.json
└── vite.config.js


## 3. Backend Structure

backend/
├── config/
├── controllers/
├── models/
├── routes/
├── middleware/
├── services/
├── utils/
├── server.js
└── package.json


## 4. Database Structure


The MongoDB database is planned to contain the following collections:
- Users
- Courses
- Enrollments
- Assignments
- Submissions
- Notifications


## 5. Folder Responsibilities


Folder	Responsibility
components	Reusable UI components
pages	Application pages
services	API communication
controllers	Handle incoming requests
models	Define database schemas
routes	Define API endpoints
middleware	Authentication and request validation
config	Database and application configuration

6. Conclusion
This proposed code structure separates application responsibilities into organized modules. It will make CampusConnect easier to develop, test, maintain, and extend in future phases.
