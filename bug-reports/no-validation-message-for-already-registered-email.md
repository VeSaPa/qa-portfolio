# Bug Report: 
No validation message is displayed for an already registered email address

## Environment:
Browser: Chrome
OS: macOS
Environment: Test environment

## Description: 
No validation message is displayed when the registration form is submitted with an already registered email address.


## Preconditions:

The email `test@test.com` is already registered.

## Steps to reproduce
1. Open the registration page
2. Enter `test@test.com` in the email field
3. Enter a valid password in the password field (e.g., `Pass1234`)
4. Enter the same password in the confirm password field
5. Click the Register button

## Expected Result:
A validation message is displayed, indicating that the email address is already registered.

## Actual Result:
No validation message is displayed after submitting the form with an already registered email address.

## Severity: 
High

## Priority:
High
