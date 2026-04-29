# BUG001 — Locked Out User Error Message Displays with Poor Formatting

## Bug Details
| Field | Value |
|---|---|
| **Bug ID** | BUG001 |
| **Feature** | Login |
| **Account Used** | locked_out_user |
| **Severity** | Low |
| **Priority** | Low |
| **Status** | Open |
| **Environment** | Chrome, Windows 11, Desktop |

---

## Summary
The error message displayed when a locked out user attempts to login wraps awkwardly and is difficult to read due to poor formatting.

## Steps to Reproduce
1. Open saucedemo.com in the browser
2. Enter username: `locked_out_user`
3. Enter password: `secret_sauce`
4. Click the **Login** button
5. Observe the error message displayed on the login form

## Expected Result
The error message should display clearly and be easy to read, ideally on a single or neatly wrapped line within the error banner.

## Actual Result
The error message text wraps across multiple lines inside a red banner, making it harder to read. The message also includes an X icon that adds to the visual clutter.

## Notes
- The login blocking itself works correctly — locked out users are successfully prevented from accessing the app
- Only the visual presentation of the error message is affected
- The functionality is correct; this is purely a UI/display issue
