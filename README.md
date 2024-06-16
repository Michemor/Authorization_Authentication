# USER AUTHORIZATION AND AUTHENTICATION

As a beginner software developer, I am undertaking this task to implement
user authorization and authentication to practice my skills in django and as
an introduction to react for frontend.

## Definitions

User authentication is the process of verifying the identity of a user who is trying to access a system. The goal is to ensure that the person is who they claim to be.

- User Sign-Up: The user provides their information (e.g., email, password) to create an account.
- User Login: The user submits their credentials to log in.
- Verification: The system checks the credentials against stored data. If they match, the user is authenticated.
- Token Issuance: Upon successful authentication, the system generates an authentication token (if using token-based authentication) and returns it to the user.
- Session Management: The system maintains the user's session, allowing access to protected resources.

User authorization is the process of determining what an authenticated user is allowed to do within the system. It defines the user's permissions and access levels to various resources and actions.

- Role Definition: Define roles and associated permissions within the system.
- Permission Assignment: Assign permissions to roles or directly to users.
- Role Assignment: Assign roles to users, determining their access level.
- Access Checks: When a user tries to perform an action or access a resource, the system checks their roles and permissions to determine if the action is allowed.