---
id: TC-EXP-003
title: Login with a username that does not exist
project: parabank-qa
module: authentication
technique: exploratory
priority: high
status: fail
bug-ref: BUG-AUTH-002
tags: [parabank-qa, authentication, exploratory, login, bug]
---

# TC-EXP-003 — Login with a username that does not exist

## Preconditions
- Browser is open on the Parabank login page (https://parabank.parasoft.com)
- User is logged out

## Steps
1. Enter a username that is not registered in the system
2. Enter any password in the Password field
3. Click the Login button

## Expected Result
System displays an error message indicating the username was not found. User remains on the login page.

## Actual Result
User is logged in and redirected to the Account Overview page of an unrelated account (displayed as John Smith) with no error message shown

## Priority
High

## Technique
Exploratory
