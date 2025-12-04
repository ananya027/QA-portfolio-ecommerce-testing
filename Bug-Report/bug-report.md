# 🐞 Bug Report

## Bug ID
BUG-LG-01

## Title
Incorrect error message displayed when email field is left empty during login.

## Module
Login

## Severity
Medium

## Priority
High

## Environment
- Application: OpenCart Demo (Localhost)
- Browser: Chrome (latest version)
- OS: Windows 10

## Description
When the user attempts to log in without entering an email, the system displays a **“No match found”** message instead of a required field validation message.  
This is incorrect behavior because validation should prevent submission of an empty email.

## Steps to Reproduce
1. Navigate to the Login page  
2. Leave the **Email** field empty  
3. Enter any value in the Password field  
4. Click the **Login** button  

## Expected Result
The system should display a validation message such as:  
- “Email is required”  
- “Please enter your email address”

## Actual Result
System displays **“No match found”** as if it validated against an actual email input.

## Screenshot
<img width="1231" height="652" alt="image" src="https://github.com/user-attachments/assets/47f7aabd-c082-4a2e-b295-e253d9cbddea" />

## Status
Open
