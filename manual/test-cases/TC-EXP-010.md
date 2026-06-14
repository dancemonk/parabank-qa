# TC-EXP-010 — Bill Pay with a negative amount

## Preconditions
- User is logged in
- User has at least one account with available balance

## Steps
1. Navigate to Bill Pay
2. Fill in all required payee fields with valid data
3. Enter a negative value in the Amount field
4. Click Send Payment

## Expected Result
System displays a validation error indicating the payment amount must be a positive value. Payment does not proceed.

## Actual Result
System displays "Payment Complete!" and processes the negative amount

## Priority
High

## Technique
Exploratory
