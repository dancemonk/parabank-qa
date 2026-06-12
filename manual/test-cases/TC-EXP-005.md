---
id: TC-EXP-005
title: Registration with a username that already exists
project: parabank-qa
module: authentication
technique: exploratory
priority: medium
status: pass
tags: [parabank-qa, authentication, exploratory, registration, validation]
---

# TC-EXP-005 — Registration with a username that already exists

## Preconditions
- Browser is open on the Parabank registration page
- A registered account with the target username already exists in the system

## Steps
1. Fill in all required registration fields with valid data
2. Enter an already-registered username in the Username field
3. Click the Register button

## Expected Result
System displays an error message indicating the username is already taken. Registration does not complete.

## Actual Result
System displays the message "This username already exists." Registration does not complete.

## Priority
Medium

## Technique
Exploratory
