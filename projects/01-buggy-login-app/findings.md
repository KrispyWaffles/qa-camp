# Findings — FoxAuth Buggy Login App

**Date:** 2026-04-16
**Tester:** Wess
**Session type:** Exploratory

## Summary


## Bugs found
| ID | Title | Severity | Status |
|----|-------|----------|--------|
| BUG-001 | success message exposes password | Critical | Reported |
| BUG-003 | user enumeration (different errors for wrong email vs wrong password) | Critical | Reported |
| BUG-007 | invalid email format accepted | Minor | Reported |
| BUG-008 | password logged into console | Critical | Reported |
| BUG-009 | Show/Hide Label Reversed | Critical | Reported |
| BUG-010 | strength bar only updates on blur | Major | Reported |
| BUG-011 | Remeber me does nothing | Minor | Reported |
| BUG-012 | Forgot password does nothing | Major | Reported |
| BUG-013 | SSO does nothing | Minor | Reported |

## Test coverage

Tested all interactive elements on the login form including form submission, 
field validation, SSO buttons, password toggle, strength meter, and auxiliary 
links. Did not test on mobile, Firefox, or Safari. Did not test with 
browser autofill.

## What I would do next

Cross-browser testing on Firefox and Safari. Test with autofilled credentials.
Test on mobile viewport. Verify bugs are reproducible after hard refresh.
Write formal test cases to cover edge cases missed in exploratory session.