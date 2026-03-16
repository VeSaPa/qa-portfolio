## Positive scenario

# TC-REG-01 Verify successful user registration with valid email and password

Steps:
1. Open the registration page
2. Enter a valid email address (e.g., `test@test.com`)
3. Enter a valid password (e.g., `Pass1234`)
4. Confirm the password
5. Click the "Register" button

Expected Result:
The user account is created successfully and a confirmation message is displayed. The user is redirected to the dashboard.

## Input validation

# TC-REG-02 Verify registration fails when the email field is empty

Steps:
1. Open the registration page
2. Leave the email field empty
3. Enter a valid password (e.g., `Pass1234`)
4. Confirm the password
5. Observe the Register button

Expected Result:
The Register button is disabled and a validation message indicating that the email field is required is displayed.

# TC-REG-03 Verify registration fails when the password field is empty

Steps:
1. Open the registration page
2. Enter a valid email address (e.g., `test@test.com`)
3. Leave the password field empty
4. Enter any value in the confirm password field
5. Observe the Register button

Expected Result:
The Register button is disabled and a validation message indicating that the password field is required is displayed.

