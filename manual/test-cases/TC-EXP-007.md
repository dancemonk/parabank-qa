# TC-EXP-007 — Transfer amount exceeding available balance

## Preconditions
- User is logged in
- User has at least two accounts

## Steps
1. Navigate to Transfer Funds
2. Select a source account in the From field
3. Select a different destination account in the To field
4. Enter an amount greater than the available balance of the source account
5. Click Transfer

## Expected Result
System displays an error indicating insufficient funds. Transfer does not proceed. Account balance remains unchanged.

## Actual Result
System displays "Transfer Complete!" and the source account balance becomes negative

## Priority
High

## Technique
Exploratory
