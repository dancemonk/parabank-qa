# TC-EXP-008 — Transfer zero amount

## Preconditions
- User is logged in
- User has at least two accounts

## Steps
1. Navigate to Transfer Funds
2. Select a source account in the From field
3. Select a different destination account in the To field
4. Enter 0 in the amount field
5. Click Transfer

## Expected Result
System displays a validation error indicating the transfer amount must be greater than zero. Transfer does not proceed.

## Actual Result
System displays "Transfer Complete!" and processes the zero-amount transfer

## Priority
High

## Technique
Exploratory
