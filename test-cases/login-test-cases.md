## Positive scenarios

# TC-LOGIN-01 Verify successful login with valid credentials 
Preconditions: User has a registered account
Steps:
1. Open the login page
2. Enter a valid email
3. Enter a valid password
4. Click the Login button

Expected Result: User is susccesfully logged in and redirected to the dashboard.

## Input validation

# TC-LOGIN-02 Verify login fails when email field is empty
Steps:
1. Open the login page
2. Leave the email field empty
3. Enter a valid password
4. Observe the Login button

Expected Result: The Login button is disabled and a validation message is displayed.

# TC-LOGIN-03 Verify login fails when password field is empty
Preconditions: User has a registered account 
Steps:
1. Open the login page
2. Enter a valid email
3. Leave the password field empty
4. Observe the Login button

Expected Result: The Login button is disabled and a validation message is displayed.

# TC-LOGIN-04 Verify login fails when both email and password fields are empty
Steps:
1. Open the login page
2. Leave the email field empty
3. Leave the password field empty
4. Observe the Login button

Expected Result: The Login button is disabled and validation messages are displayed for both required fields.
