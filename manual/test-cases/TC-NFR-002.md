# TC-NFR-002 — Password field masking on login page

## Preconditions
- Browser is open on the Parabank login page
- User is logged out

## Steps
1. Click on the Password field
2. Type any characters into the Password field
3. Observe how the entered characters are displayed

## Expected Result
All characters entered in the Password field are masked with dots or asterisks. Plain text is not visible at any point during input.

## Actual Result
All characters entered in the password field are masked with dots. Plain text is not exposed.

## Priority
High

## Technique
Non-functional — Security

## Test Level
System Testing

## Retest Type
Regression — re-run after any authentication UI changes to verify password masking is intact
