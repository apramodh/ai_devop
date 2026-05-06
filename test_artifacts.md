# Test Artifacts

## 1. Test Plan

**_Objectives_**

To verify and validate:

- Registering, logging in, and password resetting functionalities.
- Email verification and multi-factor authentication compliance with the requirement.

**_Scope_**

This test plan will cover:

- Creation of new user accounts.
- Log in for both new and old accounts.
- Reset of forgotten passwords.
- Email verification after registration.
- Multi-factor authentication enabled at login.

**_Responsibilities_**

- Test engineer will plan and design the tests.
- Test team executes the tests.
- Lead developer will fix any potential issues.
- Test engineer retests after issues have been fixed.

## 2. User Scenarios

**_Scenario 1: User Registration_**

- User goes to the registration page.
- User enters desired username, email and password and submits.
- User receives verification email and clicks the verification link.

**_Scenario 2: User Log in_**

- User goes to the login page.
- User enters username and password, and validates multi-factor authentication.
- Upon successful authentication, user is redirected to the dashboard.

**_Scenario 3: Reset Password_**

- User clicks 'Forgotten Password' on the login page.
- User enters registered email.
- User receives reset link and follows it.
- User enters new password.
 
## 3. Test Data

**_Test Data for Registration_**

- Username: TestUser123
- Email : testuser123@email.com
- Password: Testpassword@123

**_Test Data for Log in_**

- Username: TestUser123
- Password: Testpassword@123

**_Test Data for Password Reset_**

- Registered email: testuser123@email.com
- New password: Newpassword@123

Above data is used for positive scenarios. Negative testing will test system's behavior when incorrect or insufficient data is provided.