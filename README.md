# StarUML-Usecase-Diagram
Usecase Diagram Implementation in StarUML for Email System.

## Overview
This use case diagram for an email system includes actors, use cases, relationships, syntax explanation, access specifiers and feature function details.

## Actors
- **User**: Interacts with the system to perform various tasks.
- **Handler**: Manages email operations such as fetching and sending emails.
- **Authenticator**: Verifies login credentials for secure access.

## Use Cases
- **Get Email**
- **Login Credentials**
- **Update Details**
- **Send or Receive Email**

## Relationships
- Users interact with all four use cases.
- Handlers assist in email-related operations.
- Authenticators ensure secure login and data updates.

## Syntax Explanation
- Actors are represented as stick figures.
- Use cases are represented as ovals within a system boundary (rectangle).
- Lines indicate associations between actors and use cases.

## Access Specifiers
1. Public (`+`): Accessible functions like `getEmail()`, `sendEmail()`.
2. Private (`-`): Internal functions like `validateCredentials()`.
3. Protected (`#`): Inheritable functions like `encryptPassword()`.

## Feature Functions
| Use Case               | Function                            | Description                                | Access Specifier |
|------------------------|------------------------------------|--------------------------------------------|------------------|
| Get Email              | `getEmail(userID)`                 | Retrieves all emails for a user            | Public (`+`)     |
| Login Credentials      | `validateCredentials(username, password)` | Validates user credentials                | Private (`-`)    |
| Update Details         | `updateDetails(userID, newDetails)` | Updates user profile or account settings  | Public (`+`)     |
| Send or Receive Email  | `sendEmail(senderID, receiverID, message)` | Sends an email from one user to another  | Public (`+`)     |

## Conclusion
This diagram gives the simple outlook of users interaction with an email system while ensuring secure access and efficient functionality through handlers and authenticators.
