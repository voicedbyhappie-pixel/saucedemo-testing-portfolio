# TC005 — Add Product to Cart After Login

## Details
| Field | Value |
|---|---|
| **Test Case ID** | TC005 |
| **Feature** | Cart |
| **Type** | Positive test |
| **Status** | Pass |

---

## Precondition
User is logged in as standard_user and is on the products page (/inventory.html).

## Test Data
| Field | Value |
|---|---|
| Username | standard_user |
| Password | secret_sauce |
| Product | Any item on the inventory page |

---

## Test Steps
1. Open saucedemo.com and log in as `standard_user` / `secret_sauce`
2. On the products page, locate any product
3. Click the **Add to cart** button on that product
4. Observe the cart icon in the top right corner
5. Observe the button state on the product

## Expected Result
The cart badge updates to display the number 1. The "Add to cart" button changes to "Remove".

## Actual Result
Cart badge updated to 1 correctly. Button changed to "Remove" as expected.

---

## Notes
This is the entry point test for all cart-related functionality. Must pass before testing checkout flow.
