Sauce Demo Manual Testing Portfolio

A manual testing portfolio built on [Sauce Demo](https://saucedemo.com) — a web application designed specifically for testing practice.

This project demonstrates core manual QA skills including test case writing, test execution, and bug reporting.

> ⚠️ **Note:** This portfolio currently covers manual testing only. Automation testing using Playwright will be added in a future update.


## 📁 Project Structure

```
saucedemo-testing-portfolio/
│
├── test-cases/
│   ├── TC001-login-valid-credentials.md
│   ├── TC002-login-wrong-password.md
│   ├── TC003-login-locked-out-user.md
│   ├── TC004-login-empty-fields.md
│   ├── TC005-add-product-to-cart.md
│   └── TC006-problem-user-product-images.md
│
├── bug-reports/
│   ├── BUG001-locked-out-user-error-message-formatting.md
│   ├── BUG002-cart-badge-not-updating.md
│   ├── BUG003-product-prices-showing-zero.md
│   └── BUG004-cart-missing-item-after-adding-three.md
│
└── README.md
```

---

## ✅ Test Cases

Six manual test cases covering the login flow and core user journey on Sauce Demo.

| ID | Scenario | Type | Status |
|---|---|---|---|
| TC001 | Login with valid credentials | Positive | Pass |
| TC002 | Login with wrong password | Negative | Fail (expected) |
| TC003 | Login with locked out user | Negative | Fail (expected) |
| TC004 | Login with empty fields | Negative | Fail (expected) |
| TC005 | Add product to cart after login | Positive | Pass |
| TC006 | Problem user product image display | Edge case | Fail |

---

## 🐛 Bug Reports

Four bug reports documenting defects identified during manual test execution.

| ID | Title | Severity | Priority |
|---|---|---|---|
| BUG001 | Locked out user error message displays with poor formatting | Low | Low |
| BUG002 | Cart badge count does not update after adding a product | High | High |
| BUG003 | All product prices display as $0.00 on inventory page | Critical | High |
| BUG004 | Cart page shows 2 items after 3 items were added | High | High |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Sauce Demo | Practice web application used for testing |
| Chrome | Browser used for test execution |
| GitHub | Portfolio and documentation |

---

## 🧠 Skills Demonstrated

- Writing structured test cases (positive, negative, and edge case tests)
- Executing test cases manually on a real web application
- Identifying, analysing, and documenting bugs clearly
- Judging bug severity and priority
- Organising test documentation professionally

---

## 👩‍💻 About This Project

This portfolio was built as part of my journey into software testing and QA. It represents my current skill level in manual testing — covering test design, execution, and defect reporting on a real web application.

I am currently working towards adding automated test coverage using Playwright as the next phase of this project.

---

Feel free to connect with me on LinkedIn or reach out via GitHub.
