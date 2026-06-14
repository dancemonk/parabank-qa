# TC-EXP-006 — Transfer valid amount between two accounts

## Preconditions
- User is logged in
- User has at least two accounts with sufficient balance to complete a transfer

## Steps
1. Navigate to Transfer Funds
2. Select a source account in the From field
3. Select a different destination account in the To field
4. Enter a valid amount within the available balance
5. Click Transfer

## Expected Result
System displays a Transfer Complete confirmation. Source account balance decreases by the transferred amount. Destination account balance increases by the same amount.

## Actual Result
System displays "Transfer Complete!" and redirects to transfer.htm

## Priority
High

## Technique
Exploratory
