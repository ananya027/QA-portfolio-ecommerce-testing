# 🐞 Bug Report

## Bug ID
BUG-RG-01

## Title
Incorrect error message displayed when required registration fields are left empty.

## Module
Register

## Severity
Medium

## Priority
High

## Environment
- Application: OpenCart Demo (Localhost)
- Browser: Chrome (latest version)
- OS: Windows 10

## Description
When the user attempts to register without filling one or more mandatory fields, the system displays an **“Invalid credential format”** message instead of a required-field validation error.  
This is incorrect behavior because the system should alert the user that a **required field is missing**, not that the input format is wrong.

## Steps to Reproduce
1. Navigate to the **Register** page  
2. Enter valid values in some required fields  
3. Leave at least one mandatory field empty  
4. Select the **Privacy Policy** checkbox  
5. Click the **Register** button  

## Expected Result
The system should display a required-field validation message such as:  
- “This field is required”  
- “Please fill out this field”

## Actual Result
The system displays **“Invalid credential format”**, which is misleading and incorrect for missing input.

## Screenshot
<img width="1200" height="591" alt="image" src="https://github.com/user-attachments/assets/fcb8ae61-e83b-49f9-89b1-0b02e3858f3e" />


## Status
Open
