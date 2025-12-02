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

### **Flow 5: Password and Confirm Password Mismatch Flow**
The user enters a password and confirm password that do not match, and the system displays an appropriate error.

### **Flow 6: Missing Privacy Policy Agreement Flow**
The user attempts to register without checking the required privacy policy checkbox and the registration is not allowed.

### **Flow 7: Optional Newsletter Subscription Flow**
The user toggles the newsletter subscription option; registration should still succeed regardless of this selection.

---

## 📍 Module – Homepage

## 📍 Module – Search

## 📍 Module – Product Listing Page (PLP)

## 📍 Module – Product Details Page (PDP)

## 📍 Module – Cart

## 📍 Module – Wishlist

## 📍 Module – Checkout

## 📍 Module – Order Confirmation

## 📍 Module – Order History

## 📍 Module – My Account
