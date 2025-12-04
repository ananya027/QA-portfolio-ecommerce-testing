# 🐞 Bug Report

## Bug ID
BUG-OC-02

## Title
Order summary is not displayed after placing an order.

## Module
Order Confirmation

## Severity
Medium

## Priority
Medium

## Environment
- Application: OpenCart Demo (Localhost)
- Browser: Chrome (latest version)
- OS: Windows 10

## Description
After completing the checkout process, the system should display an **Order Summary** section showing product name, quantity, price, and total amount.  
However, no summary is shown — the user is taken directly to the **Order History** page without viewing any order details on a confirmation screen.

## Steps to Reproduce
1. Add any product to the cart  
2. Proceed to the **Checkout** page  
3. Enter all required details  
4. Click the **Confirm Order** button  
5. Look for an Order Summary on the resulting page  

## Expected Result
The Order Confirmation page should display a summary containing:  
- Product name  
- Quantity  
- Price  
- Total amount  

## Actual Result
No order summary is displayed.  
The user is redirected directly to the **Order History** page without seeing order details.

## Screenshot
<img width="1211" height="612" alt="image" src="https://github.com/user-attachments/assets/e836eb1e-5b7e-4fc9-b40f-88e2004aeaae" />


## Status
Open
