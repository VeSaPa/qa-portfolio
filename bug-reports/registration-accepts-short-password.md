# Bug Report: Registration accepts password shorter than required

## Environment
Browser:
Chrome
OS: 
macOS
Environment:
Test environment

## Description
The Registration form accepts a password that is shorter than the required length

## Steps to reproduce
1. Open the registration page
2. Enter any email address in the email field
3. Enter an short password (e.g., `Pass12`)
4. Enter the same password in the confirm password field
5. Click the Register button

## Expected Result
A validation message is displayed, indicating that the password is shorter than the required length

## Actual Result
No validation message is displayed, and the password is accepted

## Severity
Medium

## Priority
Medium
