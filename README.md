# 🧪 SauceDemo – Manual Testing

Manual functional testing of the [SauceDemo](https://www.saucedemo.com/) e-commerce demo app: test case design, execution, and bug reporting.

## 📌 Overview

| Item | Detail |
|---|---|
| Application under test | https://www.saucedemo.com/ |
| Testing type | Manual functional testing (positive, negative, UI, access control) |
| Test cases | 66 across 6 modules |
| Bugs reported | 4 (`SD_BUG_001` – `SD_BUG_004`) |
| Deliverables | Test case spreadsheets, bug report |
| Tools | Microsoft Excel |

## 🗂️ Modules Covered

| # | Module | Test cases | File |
|---|---|:---:|---|
| 1 | Login | 14 | [01_Login_TestCases.xlsx](test-cases/01_Login_TestCases.xlsx) |
| 2 | Products | 7 | [02_Products_TestCases.xlsx](test-cases/02_Products_TestCases.xlsx) |
| 3 | Cart | 10 | [03_Cart_TestCases.xlsx](test-cases/03_Cart_TestCases.xlsx) |
| 4 | Checkout | 15 | [04_Checkout_TestCases.xlsx](test-cases/04_Checkout_TestCases.xlsx) |
| 5 | Menu (burger menu, logout, reset state) | 11 | [05_Menu_TestCases.xlsx](test-cases/05_Menu_TestCases.xlsx) |
| 6 | Special users (`problem_user`, `error_user`) | 9 | [06_SpecialUsers_TestCases.xlsx](test-cases/06_SpecialUsers_TestCases.xlsx) |
| | **Total** | **66** | |

## 🐞 Bugs Found

Full details (steps, expected, actual, severity, priority) are in [SauceDemo_Bug_Report.xlsx](bug-reports/SauceDemo_Bug_Report.xlsx).

| Bug ID | Summary | Severity | Priority |
|---|---|:---:|:---:|
| SD_BUG_001 | Leading/trailing spaces in username are not trimmed; login fails | Medium | P0 |
| SD_BUG_002 | Product name "Test.allTheThings() T-Shirt (Red)" does not follow the "Sauce Labs …" naming format | Minor | P2 |
| SD_BUG_003 | "Sauce Labs Backpack" description contains unexpected text `carry.allTheThings()` | Medium | P1 |
| SD_BUG_004 | Invalid input on Checkout Information page is accepted with no error message | High | P0 |

## 🧾 Test Case Format

Each test case includes: ID, scenario, preconditions, steps, test data, expected result, actual result, and status (pass / fail).

## 📁 Repository Structure

```
saucedemo-manual-testing/
├── README.md
├── test-cases/        # one spreadsheet per module
├── bug-reports/       # bug report spreadsheet
└── screenshots/       # evidence for bug reports
```

## 👤 Author

**Tegar** – QA Engineer
GitHub: [@tegargr28](https://github.com/tegargr28)
