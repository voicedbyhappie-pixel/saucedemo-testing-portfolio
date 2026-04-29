# BUG002 — Cart Badge Count Does Not Update After Adding a Product

## Bug Details
| Field | Value |
|---|---|
| **Bug ID** | BUG002 |
| **Feature** | Cart |
| **Account Used** | standard_user |
| **Severity** | High |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows 11, Desktop |

---

## Summary
After adding a product to the cart, the cart badge in the top right corner does not update to reflect the number of items in the cart.

## Steps to Reproduce
1. Open saucedemo.com
2. Log in as `standard_user` / `secret_sauce`
3. On the products page, click **Add to cart** on any product
4. Observe the cart icon badge in the top right corner

## Expected Result
The cart badge should display the number **1** after one item is added to the cart.

## Actual Result
The cart badge remained empty and showed no number after the item was added. The "Add to cart" button changed to "Remove" correctly but the cart icon did not update.

## Notes
- The "Add to cart" button state updates correctly — only the cart badge count fails
- This could mislead users into thinking their item was not added
- High severity because it affects a core e-commerce feature that users rely on to track their selections
