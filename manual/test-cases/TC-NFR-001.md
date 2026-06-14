# TC-NFR-001 — Account dashboard page load performance

## Preconditions
- User is logged in
- Browser DevTools or Lighthouse is available
- Test performed on a standard broadband connection

## Steps
1. Log in to Parabank with valid credentials
2. Open Chrome DevTools → Lighthouse tab
3. Run a performance audit on the Account Overview page
4. Record LCP and INP values from the report

## Expected Result
LCP is under 2.5s (Google Good threshold). INP is under 200ms (Google Good threshold).

## Actual Result
LCP: 0.30s. INP: 16ms. Both values within Good thresholds.

## Priority
Medium

## Technique
Non-functional — Performance

## Test Level
System Testing

## Retest Type
Regression — re-run after any UI changes or infrastructure updates to verify performance has not degraded
