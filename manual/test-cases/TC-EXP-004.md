# TC-EXP-004 — Login with both fields empty

## Preconditions
- Browser is open on the Parabank login page (https://parabank.parasoft.com)
- User is logged out

## Steps
1. Leave the Username field empty
2. Leave the Password field empty
3. Click the Login button

## Expected Result
System displays a validation error prompting the user to enter a username and password. User remains on the login page.

## Actual Result
System displays the message "Please enter a username and password." User remains on the login page.

## Priority
Medium

## Technique
Exploratory
