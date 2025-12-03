# **User-Flow for E-commerce Web Application**

This document contains high-level user flows for major modules of the e-commerce application.  
Each flow represents a complete user action path and is used to derive test scenarios and test cases.

---

## 📍 Module – Login

### **Flow 1: Valid Login Flow**
The user enters valid credentials and successfully logs into the application.

### **Flow 2: Invalid Login Flow (Wrong Password)**
The user enters a valid email with an incorrect password and receives an appropriate error message.

### **Flow 3: Invalid Login Flow (Unregistered Email)**
The user enters an email that does not exist in the system and receives an error message.

### **Flow 4: Partial Input Flow**
The user fills only one field (email or password) and receives a validation error.

### **Flow 5: Email Format Validation Flow**
The user enters an improperly formatted email (e.g., "abc@", "test@com") and the system displays an email format error.

### **Flow 6: Post-Login Redirection Flow**
The user successfully logs in and is redirected to the correct account or dashboard page.

---

## 📍 Module – Register

### **Flow 1: Valid Registration Flow**
The user enters all required information correctly, agrees to the policy, and successfully creates a new account.

### **Flow 2: Registration with Existing Email**
The user enters an email that is already registered in the system and receives an error message.

### **Flow 3: Registration with Empty Mandatory Fields**
The user attempts to register without filling one or more required fields and the system displays mandatory field validation errors.

### **Flow 4: Email Format Validation Flow**
The user enters an improperly formatted email (e.g., "abc@", "user@com") and receives an invalid email format message.

### **Flow 5: Missing Privacy Policy Agreement Flow**
The user attempts to register without checking the required privacy policy checkbox and the registration is not allowed.

### **Flow 6: Optional Newsletter Subscription Flow**
The user toggles the newsletter subscription option; registration should still succeed regardless of this selection.

---

## 📍 Module – Homepage

### **Flow 1: Homepage Load Flow**
The user opens the homepage and it loads successfully with all main UI elements visible.

### **Flow 2: Header Navigation Flow**
The user clicks header menu options and is navigated to their correct pages.

### **Flow 3: Search Bar Flow**
The user accesses the search bar from the homepage and begins a search action.

### **Flow 4: Featured Products Flow**
The user clicks a featured product and is redirected to its Product Details Page.

### **Flow 5: Banner/Slider Flow**
The user interacts with homepage banners or sliders and is redirected to the correct linked page.

---

## 📍 Module – Search

### **Flow 1: Valid Search Flow**
The user searches for a valid product name or keyword and the correct matching products are displayed on the results page.

### **Flow 2: Search with Partial Keywords Flow**
The user enters a partial product name or incomplete keyword and relevant matching products appear in the results.

### **Flow 3: Invalid Search Flow (No Results)**
The user enters a search term that does not exist in the catalog, and the system shows a "No results" or equivalent message.

### **Flow 4: Empty Search Input Flow**
The user clicks the search button without entering any text, and the system either shows no results or displays an appropriate message.

### **Flow 5: Search Using Special Characters Flow**
The user enters symbols or special characters (e.g., “@#$%”) and the system handles them gracefully without errors or crashes.

### **Flow 6: Case-Insensitive Search Flow**
The user searches using uppercase, lowercase, or mixed case and the search results remain consistent.

### **Flow 7: Quick Search from Homepage Flow**
The user enters a keyword directly from the homepage search bar and is redirected to the correct results page.

### **Flow 8: Search Result Navigation Flow**
The user clicks a product from the search results page and is taken to the correct Product Details Page.

---

## 📍 Module – Product Listing Page (PLP)

### **Flow 1: PLP Load Flow**
The user opens a product category and the list of products loads successfully with basic information (image, name, price).

### **Flow 2: Open Product from PLP Flow**
The user clicks on a product from the listing page and is redirected to the correct Product Details Page (PDP).

### **Flow 3: Add to Cart from PLP Flow**
The user adds a product to the cart directly from the listing page.

### **Flow 4: Sorting Flow**
The user selects a sorting option (e.g., price or name), and the products rearrange accordingly.

### **Flow 5: No Results Flow**
If a category has no products, a “No products found” message is displayed.

---

## 📍 Module – Product Details Page (PDP)

### **Flow 1: PDP Load Flow**
The user opens a product from the Product Listing Page and the product details load correctly (image, name, price, description).

### **Flow 2: Add to Cart Flow**
The user clicks “Add to Cart” on the PDP and the product is successfully added to the cart.

### **Flow 3: Quantity Selection Flow**
The user updates the quantity field (e.g., selecting quantity 2 or entering a number), and the quantity is accepted correctly.

### **Flow 4: Image Preview Flow**
The user clicks on product image thumbnails (if available), and the main image updates accordingly.

### **Flow 5: Navigation Back to Listing Flow**
The user navigates back to the Product Listing Page using breadcrumbs or the back button, and the PLP loads normally.

---

## 📍 Module – Cart

### **Flow 1: Add to Cart from PDP/PLP Flow**
The user adds a product to the cart from either the Product Listing Page or Product Details Page and the item appears in the cart.

### **Flow 2: Update Quantity Flow**
The user changes the quantity of a cart item (e.g., from 1 to 2), and the cart updates the total price accordingly.

### **Flow 3: Remove Item Flow**
The user removes an item from the cart and the cart page updates correctly (item disappears and totals update).

### **Flow 4: Cart Persistence Flow**
The user adds items to the cart, refreshes the page or navigates away and back, and the items remain in the cart.

### **Flow 5: Proceed to Checkout Flow**
The user clicks the “Checkout” button from the cart page and is redirected to the checkout page.

---

## 📍 Module – Wishlist

### **Flow 1: Add to Wishlist Flow**
The user clicks the wishlist icon/button on a product (from PLP or PDP) and the product is successfully added to the wishlist.

### **Flow 2: Wishlist Login Requirement Flow**
If the user is not logged in, clicking “Add to Wishlist” prompts the user to log in before adding the item.

### **Flow 3: View Wishlist Page Flow**
The user navigates to the wishlist page using the header link or account menu and the wishlist items load correctly.

### **Flow 4: Remove Item from Wishlist Flow**
The user removes an item from the wishlist and the list updates accordingly.

### **Flow 5: Move to Cart Flow**
The user clicks “Add to Cart” for a product inside the wishlist and the item is added to the cart successfully.

---

## 📍 Module – Checkout

### **Flow 1: Checkout Page Load Flow**
The user clicks “Checkout” from the cart and the checkout page loads successfully with all required sections (Billing, Delivery, Payment).

### **Flow 2: Guest Checkout vs Registered Checkout Flow**
The user selects either guest checkout or login to continue, and the flow proceeds correctly (if guest checkout is available).

### **Flow 3: Billing and Delivery Details Entry Flow**
The user fills in billing and delivery details (name, address, phone) and proceeds without validation errors.

### **Flow 4: Payment Method Selection Flow**
The user selects a payment method (e.g., Cash on Delivery) and is allowed to proceed.

### **Flow 5: Order Confirmation Navigation Flow**
The user clicks “Confirm Order” and is redirected to the order confirmation page.

---

## 📍 Module – Order Confirmation

### **Flow 1: Order Confirmation Page Load Flow**
After clicking “Confirm Order,” the user is taken to the order confirmation page which loads successfully with order details.

### **Flow 2: Display Order Summary Flow**
The user views the summary (product name, quantity, price, total) and all information is accurate.

### **Flow 3: Order Success Message Flow**
The user sees a confirmation/success message indicating that the order has been placed successfully.

### **Flow 4: Navigate to Order History Flow**
The user clicks the link/button to view past orders and is redirected to the Order History page.

---

## 📍 Module – Order History

### **Flow 1: Order History Page Load Flow**
The user navigates to the Order History page from the account section, and the page loads correctly with a list of past orders.

### **Flow 2: View Order Details Flow**
The user clicks “View” or “Order Details” for a specific order and the detailed order information opens correctly.

### **Flow 3: Reorder Flow** *(If available)*
The user clicks the “Reorder” option, and the selected product(s) are added back to the cart.

### **Flow 4: No Previous Orders Flow**
If the user has no order history, the page displays an appropriate “No orders found” message.

---

## 📍 Module – My Account

### **Flow 1: My Account Page Load Flow**
The user logs in and navigates to the “My Account” page, which loads successfully with all available account options.

### **Flow 2: Edit Personal Information Flow**
The user updates their personal details (name, email, phone) and the changes are saved successfully.

### **Flow 3: Change Password Flow**
The user enters the current password and a new password, and the system updates the password successfully.

### **Flow 4: Address Book Access Flow**
The user opens the address book section and can view, add, or edit saved addresses.

### **Flow 5: Logout Flow**
The user clicks the logout button and the system logs them out successfully, redirecting them to the homepage or login page.

---
