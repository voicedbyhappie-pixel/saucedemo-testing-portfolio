# TC004 — Login with Empty Fields

## Details
| Field | Value |
|---|---|
| **Test Case ID** | TC004 |
| **Feature** | Login |
| **Type** | Negative test |
| **Status** | Fail (expected — form should not submit) |

---

## Precondition
Browser is open on saucedemo.com. Both username and password fields are empty.

## Test Data
No data — both fields left blank.

---

## Test Steps
1. Open saucedemo.com in the browser
2. Leave the username field blank
3. Leave the password field blank
4. Click the **Login** button

## Expected Result
The form does not submit. A validation error appears: "Username is required". User remains on the login page.

## Actual Result
Validation error displayed correctly. Form did not proceed without credentials.

---

## Notes
Basic form validation test. Ensures the application does not allow empty submissions.
