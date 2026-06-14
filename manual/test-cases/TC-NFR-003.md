# TC-NFR-003 — Error message clarity on failed login attempt

## Preconditions
- Browser is open on the Parabank login page
- User is logged out

## Steps
1. Leave both Username and Password fields empty
2. Click the Login button
3. Read the error message displayed by the system

## Expected Result
Error message clearly identifies what went wrong and what the user must do to proceed. Language is plain, not technical. No stack trace or internal error code is exposed.

## Actual Result
System displays "Please enter a username and password." Message is clear and actionable. No technical details exposed.

## Priority
Medium

## Technique
Non-functional — Usability

## Test Level
System Testing

## Retest Type
Regression — re-run after any authentication UI or copy changes to verify error messages remain clear and non-technical
