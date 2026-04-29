# BUG004 — Cart Page Shows 2 Items After 3 Items Were Added

## Bug Details
| Field | Value |
|---|---|
| **Bug ID** | BUG004 |
| **Feature** | Cart |
| **Account Used** | standard_user |
| **Severity** | High |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows 11, Desktop |

---

## Summary
After adding 3 products to the cart, the cart page only displays 2 items. One item is missing from the cart view despite being successfully added from the products page.

## Steps to Reproduce
1. Open saucedemo.com
2. Log in as `standard_user` / `secret_sauce`
3. On the products page, click **Add to cart** on the first product
4. Click **Add to cart** on the second product
5. Click **Add to cart** on the third product
6. Click the cart icon in the top right corner
7. Observe the number of items listed on the cart page

## Expected Result
All 3 added items should appear on the cart page. Cart badge should show 3.

## Actual Result
Only 2 items appeared on the cart page. The third item added was missing from the cart view. The cart badge showed 3 correctly but the cart page only listed 2 items.

## Notes
- The cart badge count (3) and the cart page item count (2) are out of sync — this suggests the display and underlying cart data may not be consistent
- The missing item appears to be whichever product was added last
- High severity because users could lose items from their cart without knowing, directly impacting the purchase flow
