# Backend Folder Structure

This document describes the recommended folder structure for the backend of this project.

```
backend/
│
├── controller/   # Contains all controller files (business logic)
│
├── routes/       # Contains all route definitions
│
├── test/         # Contains test files
│
├── middleware/   # Contains middleware functions
│
└── utils/        # Contains utility/helper functions
```

## Folder Descriptions

- **controller/**: Handles the main logic for each route, interacts with models/services.
- **routes/**: Defines API endpoints and connects them to controllers.
- **test/**: Contains unit and integration tests for the backend.
- **middleware/**: Functions that process requests before they reach controllers (e.g., authentication, logging).
- **utils/**: Utility functions and helpers used throughout the backend.
