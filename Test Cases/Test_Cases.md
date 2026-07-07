# Test Cases

| Test ID | Test Scenario | Test Steps | Expected Result | Actual Result | Status |
|---------|---------------|------------|-----------------|---------------|--------|
| TC001 | Login with valid credentials | Enter standard_user and secret_sauce, then click Login | User successfully logs in and reaches the products page | Pass | ✅ Pass |
| TC002 | Login with incorrect password | Enter standard_user and an incorrect password | Error message displayed | Pass | ✅ Pass |
| TC003 | Login with empty username | Leave username blank and attempt login | Error message displayed | Pass | ✅ Pass |
| TC004 | Login with empty password | Leave password blank and attempt login | Error message displayed | Pass | ✅ Pass |
| TC005 | Add an item to the cart | Login and click "Add to Cart" on a product | Shopping cart badge updates to show one item | Pass | ✅ Pass |
| TC006 | Remove an item from the cart | Remove the previously added item | Shopping cart becomes empty | Pass | ✅ Pass |
| TC007 | View the shopping cart | Click the shopping cart icon | Shopping cart page displays selected items | Pass | ✅ Pass |
| TC008 | Complete checkout | Add an item, enter checkout information and finish purchase | Order confirmation page displayed | Pass | ✅ Pass |
| TC009 | Logout | Open the menu and click Logout | User returns to the login page | Pass | ✅ Pass |
| TC010 | Access protected page after logout | Logout and press the browser Back button | User should not regain access without logging in again | Pass | ✅ Pass |
