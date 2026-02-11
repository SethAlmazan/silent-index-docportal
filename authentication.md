# Authentication

**Location:** Project Homepage > Authentication

## Functional Description
This module handles user authentication and access control within the Silent Index system. It ensures that only authorized personnel can log in and access system features based on their assigned roles.

## Use Case Scenario

### UC-AUTH-01: User Login
| Actor | User |
|---|---|
| Precondition | User has a registered account |
| Trigger | User clicks “Login” |
| Main Flow | 1. User enters username and password. <br> 2. System validates credentials. <br> 3. System grants access and redirects to dashboard. |
| Alternate Flow | A1: Invalid credentials → system shows error message |
| Postcondition | User is logged in |
