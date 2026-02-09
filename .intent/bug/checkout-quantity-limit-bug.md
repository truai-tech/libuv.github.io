*   **Summary:** Users are unable to complete checkout when adding more than 10 of a specific item to their cart.
*   **Expected Behavior:** Users should be able to add any quantity of an item to their cart and proceed to checkout.
*   **Actual Behavior:** When a user adds more than 10 of "Limited Edition T-Shirt" to their cart, the checkout button becomes disabled and an error message "Quantity limit exceeded" appears.
*   **Steps to Reproduce:**
    1.  Navigate to the product page for "Limited Edition T-Shirt."
    2.  Add 11 or more of the item to the cart.
    3.  Observe that the checkout button is disabled and the error message is displayed.
*   **Impact:** Customers who want to purchase more than 10 of a specific item are unable to complete their purchase, leading to lost sales and frustration.
*   **Possible Cause:** There may be a validation rule in the shopping cart logic that incorrectly limits the quantity of "Limited Edition T-Shirt" to 10. This could be due to a configuration error or a bug in the code.