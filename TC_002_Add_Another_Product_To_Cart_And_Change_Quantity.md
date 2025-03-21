# Test Case ID: TC_002_Add_Another_Product_To_Cart_And_Change_Quantity

**Title:** Add another product to the cart and change its quantity

**Tested Page:** https://demo.opencart.com/

**Priority:** High  
**Test Type:** Manual  
**Precondition:** User is on the homepage of the OpenCart demo site  
**Tested By:** Hakicu 
**Date:** 24/11/2024

---

## Description:
This test case verifies that the user can successfully add a different product to the cart, change its quantity, and ensure the cart is updated accordingly.

---

## Test Steps:

| Step | Action |
|------|--------|
| 1 | Go to https://demo.opencart.com/ |
| 2 | Hover over or click the "Laptops & Notebooks" menu |
| 3 | Select “Show All Laptops & Notebooks” |
| 4 | Click on the product titled “HP LP3065” |
| 5 | Click on the “Add to Cart” button |
| 6 | Navigate to the cart by clicking the cart icon at the top right |
| 7 | Click on “View Cart” |
| 8 | In the cart, change the quantity of the HP LP3065 product to 2 |
| 9 | Click the “Update” button to update the cart |
| 10 | Verify that the total price has been updated based on the new quantity |
| 11 | Click on the “Checkout” button |

---

## Expected Result:
- The HP LP3065 product should be successfully added to the cart with the correct quantity (2).
- The total price in the cart should reflect the updated quantity.
- User should be able to proceed to checkout without errors.

---

## Postcondition:
User is redirected to the checkout page with the updated cart, which includes the HP LP3065 product with the updated quantity.

---

## Notes:
- Make sure the cart is updated instantly when the quantity is changed.
- Test should be repeated with different quantities for edge case validation.
