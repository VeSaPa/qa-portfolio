## Positive scenarios

# TC-LOGIN-01 Verify successful login with valid credentials 
Preconditions: User has a registered account

Steps:
1. Open the login page
2. Enter a valid email
3. Enter a valid password
4. Click the Login button

Expected Result: 
User is susccessfully logged in and redirected to the dashboard.

## Input validation

# TC-LOGIN-02 Verify login fails when email field is empty

Steps:
1. Open the login page
2. Leave the email field empty
3. Enter a valid password
4. Observe the Login button

Expected Result: 
The Login button is disabled and a validation message is displayed.

# TC-LOGIN-03 Verify login fails when password field is empty
Preconditions: User has a registered account 

Steps:
1. Open the login page
2. Enter a valid email
3. Leave the password field empty
4. Observe the Login button

Expected Result: 
The Login button is disabled and a validation message is displayed.

# TC-LOGIN-04 Verify login fails when both email and password fields are empty
Steps:
1. Open the login page
2. Leave the email field empty
3. Leave the password field empty
4. Observe the Login button

Expected Result: 
The Login button is disabled and validation messages are displayed for both required fields.

# TC-LOGIN-05 Verify system shows validation message for invalid email format

Steps: 
1. Open the login page
2. Enter an invalid email format (e.g., test@com, test.com, test@)
3. Enter a valid password
4. Observe the validation message

Expected Result: 
A validation message is displayed indicating that the email format is invalid.


## Authentication Errors

# TC-LOGIN-06 Verify error message appears when an incorrect password is entered
Preconditions: User has a registered email address

Steps:
1. Open the login page
2. Enter the registered email address
3. Enter an incorrect password
4. Click the Login button

Expected Result: 
An authentication error message is displayed indicating that the email or password is incorrect.

# TC-LOGIN-07 Verify error message appears when an unregistered email is entered

Steps:
1. Open the login page
2. Enter an unregistered email address
3. Enter any password
4. Click the Login button

Expected Result:
An authentication error message is displayed indicating that the email or password is incorrect.

## UI / security

# TC-LOGIN-08 Verify password field masks entered characters

Steps:
1. Open the login page
2. Enter any email address
3. Enter any password
4. Observe the password field

Expected Result:
The entered characters in the password field are masked (displayed as dots)

# TC-LOGIN-09 Verify Login button is disabled when required fields are empty

Steps:
1. Open the login page
2. Leave the email address field empty
3. Leave the password field empty
4. Observe the Login button

Expected Result:
The Login button is disabled and cannot be clicked.

## Navigation

# TC-LOGIN-10 Verify "Forgot Password" link redirects to password reset page

Steps:
1. Open the login page
2. Click the "Forgot Password" link

Expected Result:
The user is redirected to the password reset page.

# TC-LOGIN-11 Verify user can navigate to the registration page from the login page

Steps:
1. Open the login page
2. Click the "Register Now" link

Expected Result:
The user is redirected to the registration page.
