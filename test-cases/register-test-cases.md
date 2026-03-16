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

# TC-REG-04 Verify registration fails when both email and password fields are empty

Steps:
1. Open the registration page
2. Leave the email field empty
3. Leave the password field empty
4. Enter any value in the confirm password field
5. Observe the Register button

Expected Result:
The Register button is disabled and a validation messages indicating that the email and password fields are required is displayed.

# TC-REG-05 Verify a validation message appears for an invalid email format

Steps:
1. Open the registration page
2. Enter an invalid email address (e.g., `test@.com`)
3. Enter a valid password (e.g., `Pass1234`)
4. Confirm the password
5. Observe the Register button

Expected Result:
The Register button is disabled and a validation message indicating that the email format is invalid is displayed.

# TC-REG-06 Verify a validation message appears when the password is shorter than the required length (BVA)

Steps:
1. Open the registration page
2. Enter a valid email address (e.g., `test@test.com`)
3. Enter a password shorter than the required length (e.g., `Pass123`)
4. Enter any value in the confirm password field
5. Observe the Register button

Expected Result:
The Register button is disabled and a validation message indicating that the password must be at least 8 characters long is displayed.

# TC-REG-07 Verify a validation message appears when the password and confirm password do not match

Steps:
1. Open the registration page
2. Enter a valid email address (e.g., `test@test.com`)
3. Enter a valid password (e.g., `Pass1234`)
4. Enter a different password in the confirm password field (e.g., `Pass4321`)
5. Observe the Register button

Expected Result:
The Register button is disabled and a validation message indicating that passwords do not match is displayed.


