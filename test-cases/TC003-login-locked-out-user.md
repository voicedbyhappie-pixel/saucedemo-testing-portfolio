# TC003 — Login with Locked Out User

## Details
| Field | Value |
|---|---|
| **Test Case ID** | TC003 |
| **Feature** | Login |
| **Type** | Negative test |
| **Status** | Fail (expected — account is locked) |

---

## Precondition
Browser is open on saucedemo.com. No user is currently logged in.

## Test Data
| Field | Value |
|---|---|
| Username | locked_out_user |
| Password | secret_sauce |

---

## Test Steps
1. Open saucedemo.com in the browser
2. Enter username: `locked_out_user`
3. Enter password: `secret_sauce`
4. Click the **Login** button

## Expected Result
An error message appears: "Sorry, this user has been locked out." User cannot access the products page.

## Actual Result
Error message displayed correctly. User was blocked from accessing the application.

---

## Notes
This test verifies that account-level access control works correctly. A locked account should never reach the products page regardless of correct credentials.
