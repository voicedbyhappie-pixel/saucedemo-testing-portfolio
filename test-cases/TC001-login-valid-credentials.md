# TC001 — Login with Valid Credentials

## Details
| Field | Value |
|---|---|
| **Test Case ID** | TC001 |
| **Feature** | Login |
| **Type** | Positive test |
| **Status** | Pass |

---

## Precondition
Browser is open on saucedemo.com. No user is currently logged in.

## Test Data
| Field | Value |
|---|---|
| Username | standard_user |
| Password | secret_sauce |

---

## Test Steps
1. Open saucedemo.com in the browser
2. Enter username: `standard_user`
3. Enter password: `secret_sauce`
4. Click the **Login** button

## Expected Result
User is redirected to the products page (`/inventory.html`). The page title displays "Products". No error message is shown.

## Actual Result
User was successfully redirected to the inventory page. Products page loaded correctly with all items visible.

---

## Notes
This is the baseline positive test. All other login tests are variations of this scenario.
