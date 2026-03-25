# Bug Report: No error message is displayed when an incorrect password is entered

## Environment
Browser: 
Chrome
OS:
macOS
Environment:
Test environment

## Description
After entering an incorrect password, no authentication error message is displayed.

## Preconditions
The email address `test@test.com` is already registered with password `Pass1234`.

## Steps to reproduce
1. Open the login page
2. Enter `test@test.com` in the email field
3. Enter `1234Pass` in the password field
4. Click the Login button

## Expected Result
An authentication error message is displayed, indicating that the email or password is incorrect.

## Actual Result
No authentication error message is displayed.

## Severity
High

## Priority
High
