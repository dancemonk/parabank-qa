---
id: TC-EXP-002
title: Login with wrong password
project: parabank-qa
module: authentication
technique: exploratory
priority: high
status: fail
bug-ref: BUG-AUTH-001
tags: [parabank-qa, authentication, exploratory, login, bug]
---

# TC-EXP-002 — Login with wrong password

## Preconditions
- User has a registered Parabank account
- Browser is open on the Parabank login page (https://parabank.parasoft.com)
- User is logged out

## Steps
1. Enter a valid registered username in the Username field
2. Enter an incorrect password for that account in the Password field
3. Click the Login button

## Expected Result
System displays an error message indicating invalid credentials. User remains on the login page. Login does not proceed.

## Actual Result
User is redirected to the Account Overview page displaying account names, balances, and available amounts — login succeeds despite the wrong password

## Priority
High

## Technique
Exploratory
