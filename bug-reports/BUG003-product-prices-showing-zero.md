# BUG003 — All Product Prices Display as $0.00 on Inventory Page

## Bug Details
| Field | Value |
|---|---|
| **Bug ID** | BUG003 |
| **Feature** | Product Display |
| **Account Used** | standard_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows 11, Desktop |

---

## Summary
All products on the inventory page display a price of $0.00 instead of their correct prices.

## Steps to Reproduce
1. Open saucedemo.com
2. Log in as `standard_user` / `secret_sauce`
3. Navigate to the products page
4. Observe the price displayed under each product

## Expected Result
Each product should display its correct price (e.g. $29.99, $9.99, $15.99).

## Actual Result
All products displayed a price of **$0.00**. No correct prices were shown for any item on the page.

## Notes
- Severity is Critical because incorrect pricing data is a business-critical failure
- In a real store, customers could potentially add items to cart at $0.00
- Affects all products — this is not isolated to a single item
- This is a data display failure, not a cosmetic issue
