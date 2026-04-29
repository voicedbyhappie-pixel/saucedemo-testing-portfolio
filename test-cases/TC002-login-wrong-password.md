# TC002 — Login with Wrong Password

## Details
| Field | Value |
|---|---|
| **Test Case ID** | TC002 |
| **Feature** | Login |
| **Type** | Negative test |
| **Status** | Fail (expected — login should be blocked) |

---

## Precondition
Browser is open on saucedemo.com. No user is currently logged in.

## Test Data
| Field | Value |
|---|---|
| Username | standard_user |
| Password | wrongpassword123 |

---

## Test Steps
1. Open saucedemo.com in the browser
2. Enter username: `standard_user`
3. Enter password: `wrongpassword123`
4. Click the **Login** button

## Expected Result
An error message appears: "Username and password do not match any user in this service". User remains on the login page and is not redirected.

## Actual Result
Error message displayed correctly. User was not granted access to the products page.

---

## Notes
This test confirms the system correctly rejects invalid credentials and does not expose any part of the application to unauthorised users.
