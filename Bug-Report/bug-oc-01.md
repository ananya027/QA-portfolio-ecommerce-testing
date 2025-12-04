# 🐞 Bug Report

## Bug ID
BUG-OC-01

## Title
Order confirmation page does not appear after placing an order; user is redirected directly to Order History.

## Module
Order Confirmation

## Severity
High

## Priority
High

## Environment
- Application: OpenCart Demo (Localhost)
- Browser: Chrome (latest version)
- OS: Windows 10

## Description
After clicking the **Confirm Order** button, the system should display a dedicated **Order Confirmation** page with order details.  
Instead, the user is redirected directly to the **Order History** page, and no confirmation page is shown.

## Steps to Reproduce
1. Add any product to the cart  
2. Proceed to the **Checkout** page  
3. Fill in all required billing and delivery details  
4. Click the **Confirm Order** button  
5. Observe the page that loads  

## Expected Result
A full **Order Confirmation** page should appear showing:  
- Order details  
- Product summary  
- Prices and totals  
- Order success message  

## Actual Result
The system **skips the confirmation page** entirely and redirects directly to the **Order History** page.

## Screenshot
<img width="1211" height="612" alt="image" src="https://github.com/user-attachments/assets/64f7e15f-4cad-407e-a199-406c785a8529" />


## Status
Open
