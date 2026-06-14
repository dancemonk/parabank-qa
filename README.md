# Parabank QA Portfolio

A QA portfolio project built against [Parabank](https://parabank.parasoft.com), a demo banking application by Parasoft. The project covers manual testing, REST API testing, and UI automation across core banking flows: authentication, fund transfers, loan requests, and bill payment.

All work follows ISTQB CTFL v4.0 methodology.

---

## What's Inside

| Folder | Contents |
|--------|----------|
| `manual/` | Test cases, bug reports, test documentation |
| `api-testing/` | Postman collection and Python pytest suite for the Parabank REST API |
| `automation/` | Playwright and Python UI automation suite using Page Object Model |
| `docs/` | Cheat sheets and study reference materials |

---

## Test Coverage

**Manual Testing**
- Exploratory test cases covering authentication, fund transfers, and bill pay
- Formal test cases using Equivalence Partitioning, Boundary Value Analysis, Decision Table Testing, and State Transition Testing
- Bug reports with severity, priority, steps to reproduce, and expected vs actual results

**Documentation**
- Test Plan with scope, objectives, entry/exit criteria, and risk register
- Requirements Traceability Matrix mapping test cases to business requirements
- Test Summary Report with pass/fail breakdown, defect summary, and coverage percentage

**API Testing**
- Postman collection covering authentication, accounts, transfers, and loan endpoints
- Python requests and pytest suite with schema validation, negative scenarios, and edge cases

**UI Automation**
- Playwright and pytest suite with Page Object Model structure
- Covers login, account management, fund transfers, and loan request flows
- Integrated with GitHub Actions CI

---

## Tech Stack

| Area | Tools |
|------|-------|
| Manual testing | Parabank UI, Markdown |
| API testing | Postman, Python, pytest, requests |
| UI automation | Playwright, Python, pytest, Page Object Model |
| CI/CD | GitHub Actions |

---

## Application Under Test

[Parabank](https://parabank.parasoft.com) by Parasoft. A publicly hosted demo banking application with a full web UI and REST API. No local setup required.
