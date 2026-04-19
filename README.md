# Test Case Management System

## Test Case Planning – SauceDemo Web App Functional Testing

## What is a Test Plan?

A Test Plan is a formal document that defines the scope, objectives, strategy, resources, and schedule of testing activities for a software project. It serves as a blueprint to ensure that all testing efforts are well-structured, organized, and aligned with project requirements.

In test management tools like Kiwi TCMS, a Test Plan represents a collection of test cases grouped together to validate a specific feature, module, or entire application.

## Purpose of the Test Plan

The Test Plan helps to:

- Define what needs to be tested  
- Outline testing strategy and approach  
- Organize test cases into a structured flow  
- Assign responsibilities and resources  
- Track testing progress and results  
- Ensure complete coverage of application functionality  

## Test Plan in This Project

For the **SauceDemo Web App Testing** project, the Test Plan includes all functional test scenarios related to the web application.

### 📄 Test Plan Name:
**SauceDemo Web App Testing**

## Scope of Testing

The Test Plan covers the following modules:

### Login Functionality
- Valid login  
- Invalid login

<img width="1902" height="863" alt="TC-01" src="https://github.com/user-attachments/assets/f863fdbe-0801-4c97-a957-28afcb19eae7" />
<img width="1899" height="860" alt="TC-02" src="https://github.com/user-attachments/assets/ae6d10c0-f8da-45b3-afab-22efc2041fc3" />

### Inventory Management
- View products  
- Add items to cart

<img width="1896" height="861" alt="TC-03" src="https://github.com/user-attachments/assets/077c89ac-90b7-4187-85c2-18446bcc6c0b" />

### Cart Functionality
- View cart items  
- Navigate to checkout

<img width="1901" height="888" alt="TC-04" src="https://github.com/user-attachments/assets/66b1fbbf-5f36-4899-a78d-57cc697acdc1" />
<img width="1903" height="885" alt="TC-05" src="https://github.com/user-attachments/assets/66d8f794-a04b-477e-9f48-2bd7b6886080" />

### Checkout Process
- Enter user information  
- Complete purchase

<img width="1902" height="887" alt="TC-06" src="https://github.com/user-attachments/assets/3d69da0a-aa0b-4b32-87c8-a32e2b5149e8" />
<img width="1903" height="885" alt="TC-07" src="https://github.com/user-attachments/assets/5bdfac21-bf57-4fd9-a50b-7d4f156624c3" />

### Logout Functionality
- User is logged out  
- Redirected to login page

<img width="1903" height="859" alt="TC-08" src="https://github.com/user-attachments/assets/2b13b17c-3608-48bf-8737-27af929f09ed" />

## Test Strategy

- **Type of Testing:** Functional Testing  
- **Approach:**
  - Manual test case design using Kiwi TCMS  
  - Automated test execution using Selenium and Pytest  
- **Design Pattern:** Page Object Model (POM)  
- **Test Data:** JSON-based input data  

## Test Environment

- **Application:** SauceDemo Web Application  
- **URL:** https://www.saucedemo.com/  
- **Browser:** Google Chrome  
- **Automation Tool:** Selenium WebDriver  
- **Test Framework:** Pytest  
- **Reporting Tools:** Allure Reports, Excel (openpyxl)  

## Test Execution

- Test cases are executed using Pytest automation scripts  
- Results are:
  - Visualized using Allure Reports  
  - Logged into Excel for defect tracking  
  - Updated in Kiwi TCMS for traceability  

## Defect Management

Failed test cases are logged automatically in Excel.

Each defect includes:

- Test Case Name  
- Error Message  
- Status (Fail)  
- Timestamp  
- Expected Outcome  

## Objectives

- Ensure all core functionalities of SauceDemo are working correctly  
- Identify defects early in the testing cycle  
- Maintain a structured and traceable testing workflow  

## Conclusion

The Test Plan provides a structured approach to testing, ensuring that all functionalities are validated efficiently.

By combining test management through Kiwi TCMS with automation using Selenium and Pytest, this project demonstrates a complete and professional QA workflow.
