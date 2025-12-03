# **Test Scenarios for E-Commerce Web Application**

This document contains high-level test scenarios derived from the user flows.  
Each scenario describes a testable condition to verify core functionality across major modules.

---

## 📍 Module – Login

### TS-LG-01: Verify login with valid email and valid password.
### TS-LG-02: Verify login with valid email and invalid password.
### TS-LG-03: Verify login with unregistered email.
### TS-LG-04: Verify login with empty email field.
### TS-LG-05: Verify login with empty password field.
### TS-LG-06: Verify login with both fields empty.
### TS-LG-07: Verify login with invalid email format.
### TS-LG-08: Verify error message for incorrect credentials.
### TS-LG-09: Verify successful redirection after valid login.
### TS-LG-10: Verify login behavior after clicking browser back button post-logout.

---

## 📍 Module – Register

### TS-RG-01: Verify user can register successfully with all valid inputs.
### TS-RG-02: Verify registration fails when using an already registered email.
### TS-RG-03: Verify registration with empty mandatory fields shows appropriate validation errors.
### TS-RG-04: Verify registration with an invalid email format shows an error message.
### TS-RG-05: Verify error when password and confirm password fields do not match.
### TS-RG-06: Verify user cannot register without accepting the privacy policy.
### TS-RG-07: Verify registration succeeds regardless of newsletter subscription selection.
### TS-RG-08: Verify successful redirection after completing registration.

---
## 📍 Module – Homepage

### TS-HP-01: Verify the homepage loads successfully with all major UI elements.
### TS-HP-02: Verify header navigation links navigate to their correct pages.
### TS-HP-03: Verify the search bar is visible, accessible, and accepts input.
### TS-HP-04: Verify featured products load correctly and navigate to the Product Details Page when clicked.
### TS-HP-05: Verify homepage banners/sliders redirect to the correct linked page or category.

---

## 📍 Module – Search

### TS-SR-01: Verify searching with a valid product name displays correct results.
### TS-SR-02: Verify searching with partial keywords shows relevant matching products.
### TS-SR-03: Verify searching with an invalid/non-existent keyword displays “No results” or equivalent message.
### TS-SR-04: Verify clicking search with an empty input shows appropriate behavior (no results or warning).
### TS-SR-05: Verify search handles special characters without errors or crashes.
### TS-SR-06: Verify search results are consistent for uppercase, lowercase, and mixed case input.
### TS-SR-07: Verify user can perform a search directly from the homepage search bar.
### TS-SR-08: Verify clicking a product from search results navigates to the correct Product Details Page.

---

## 📍 Module – Product Listing Page (PLP)

### TS-PLP-01: Verify PLP loads correctly when a user opens a product category.
### TS-PLP-02: Verify each product displays basic information (image, name, price).
### TS-PLP-03: Verify clicking a product from the PLP opens the correct Product Details Page (PDP).
### TS-PLP-04: Verify user can add a product to the cart directly from the PLP.
### TS-PLP-05: Verify sorting options (e.g., price or name) rearrange products correctly.
### TS-PLP-06: Verify PLP displays “No products found” when a category contains no items.

---

## 📍 Module – Product Details Page (PDP)

### TS-PDP-01: Verify PDP loads correctly when a product is opened from the PLP.
### TS-PDP-02: Verify PDP displays correct product information (image, name, price, description).
### TS-PDP-03: Verify user can add a product to the cart from the PDP.
### TS-PDP-04: Verify user can update the product quantity on the PDP.
### TS-PDP-05: Verify clicking product image thumbnails updates the main image preview (if multiple images exist).
### TS-PDP-06: Verify user can navigate back to the PLP using breadcrumbs or browser navigation.

---

## 📍 Module – Cart

### TS-CT-01: Verify product added from PDP/PLP appears correctly in the cart.
### TS-CT-02: Verify user can update item quantity in the cart.
### TS-CT-03: Verify total price updates correctly when quantity is changed.
### TS-CT-04: Verify user can remove an item from the cart.
### TS-CT-05: Verify cart updates correctly after removing an item.
### TS-CT-06: Verify cart items persist after page refresh.
### TS-CT-07: Verify cart items persist when navigating away and returning to the cart.
### TS-CT-08: Verify user can proceed to checkout from the cart page.

---

## 📍 Module – Wishlist

### TS-WL-01: Verify user can add a product to the wishlist from PLP/PDP.
### TS-WL-02: Verify system prompts login when adding to wishlist as a guest user.
### TS-WL-03: Verify wishlist page loads correctly with all saved items.
### TS-WL-04: Verify user can remove an item from the wishlist.
### TS-WL-05: Verify user can add a wishlist item to the cart.

---

## 📍 Module – Checkout

### TS-CK-01: Verify checkout page loads correctly with all required sections (Billing, Delivery, Payment).
### TS-CK-02: Verify user can proceed with registered checkout after logging in.
### TS-CK-03: Verify user can proceed with guest checkout (if available).
### TS-CK-04: Verify user can enter valid billing and delivery details.
### TS-CK-05: Verify validation messages appear for missing or incorrect details.
### TS-CK-06: Verify user can select a payment method successfully.
### TS-CK-07: Verify user can proceed to the order confirmation step after selecting payment.

---

## 📍 Module – Order Confirmation

### TS-OC-01: Verify the order confirmation page loads after completing checkout.
### TS-OC-02: Verify order summary displays correct details (product, quantity, price, total).
### TS-OC-03: Verify success message appears indicating order was placed successfully.
### TS-OC-04: Verify user can navigate to the Order History page from the confirmation page.

---

## 📍 Module – Order History

### TS-OH-01: Verify Order History page loads correctly for a logged-in user.
### TS-OH-02: Verify past orders are displayed with correct details (order ID, date, status).
### TS-OH-03: Verify user can view detailed information for a specific order.
### TS-OH-04: Verify user can reorder an item from their past orders (if feature is available).
### TS-OH-05: Verify appropriate message is displayed when no past orders exist.

---

## 📍 Module – My Account

### TS-MA-01: Verify My Account page loads correctly after login.
### TS-MA-02: Verify user can update personal information successfully.
### TS-MA-03: Verify validation messages appear for invalid or missing personal details.
### TS-MA-04: Verify user can change their account password using valid current password.
### TS-MA-05: Verify error message appears when entering incorrect current password.
### TS-MA-06: Verify user can view, add, and edit addresses in the Address Book section.
### TS-MA-07: Verify user is logged out successfully when clicking the Logout option.
### TS-MA-08: Verify user is redirected correctly after logging out.

---
