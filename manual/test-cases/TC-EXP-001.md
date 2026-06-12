---
id: TC-EXP-001
title: Login with valid credentials
project: parabank-qa
module: authentication
technique: exploratory
priority: high
status: pass
tags: [parabank-qa, authentication, exploratory, login]
---

# TC-EXP-001 — Login with valid credentials

## Preconditions
- User has a registered Parabank account
- Browser is open on the Parabank login page (https://parabank.parasoft.com)
- User is logged out

## Steps
1. Enter a valid registered username in the Username field
2. Enter the correct password for that account in the Password field
3. Click the Login button

## Expected Result
User is redirected to the Account Overview page displaying account names, balances, and available amounts

## Actual Result
User is redirected to the Account Overview page displaying account names, balances, and available amounts

## Priority
High

## Technique
Exploratory
