# Bluesky – Manual QA Test Cases

This repository contains manual test cases created for the [Bluesky](https://bsky.app/) frontend web application. The test cases are written in Excel and cover core functionalities such as:

- Sign Up
- Sign In
- Password validation and related scenarios

The purpose of this project is to practice manual testing concepts including test case design, functional testing, and defect identification.

---

## Test Summary

| Module | Test Cases | Pass | Fail |
|---|---|---|---|
| Sign Up | 12 | 10 | 2 |
| Sign In | 9 | 9 | 0 |
| Password | 9 | 6 | 3 |
| **Total** | **30** | **25** | **5** |

---

## Bug Reports

5 bugs were identified and logged during test execution.

| Bug ID | Summary | Severity | Priority |
|---|---|---|---|
| B1 | Password change confirmation email not sent | Major | P0 |
| B2 | Duplicate email registration shows no warning | Major | P0 |
| B3 | User can log in with old password after reset | Critical | P0 |
| B4 | Minimum age (13+) not enforced during Sign Up | Critical | P0 |
| B5 | Session not terminated after password change | Major | P1 |

---

## Tools Used

- MS Excel – Test case documentation
- Jira (practice) – Bug tracking and defect logging

---

## Author

**Arundhyuti** · Manual QA Practice Project · November 2024

*Test cases reflect application behaviour as of November 2024.*
