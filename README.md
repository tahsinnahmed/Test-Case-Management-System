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

### 🔐 Login Functionality
- Valid login  
- Invalid login  

### 📦 Inventory Management
- View products  
- Add items to cart  

### 🛒 Cart Functionality
- View cart items  
- Navigate to checkout  

### 💳 Checkout Process
- Enter user information  
- Complete purchase  

---

## 🧭 Test Strategy

- **Type of Testing:** Functional Testing  
- **Approach:**
  - Manual test case design using Kiwi TCMS  
  - Automated test execution using Selenium and Pytest  
- **Design Pattern:** Page Object Model (POM)  
- **Test Data:** JSON-based input data  

---

## 💻 Test Environment

- **Application:** SauceDemo Web Application  
- **URL:** https://www.saucedemo.com/  
- **Browser:** Google Chrome  
- **Automation Tool:** Selenium WebDriver  
- **Test Framework:** Pytest  
- **Reporting Tools:** Allure Reports, Excel (openpyxl)  

## ▶️ Test Execution

- Test cases are executed using Pytest automation scripts  
- Results are:
  - Visualized using Allure Reports  
  - Logged into Excel for defect tracking  
  - Updated in Kiwi TCMS for traceability  

## 🐞 Defect Management

Failed test cases are logged automatically in Excel.

Each defect includes:

- Test Case Name  
- Error Message  
- Status (Fail)  
- Timestamp  
- Expected Outcome  

## 🎯 Objectives

- Ensure all core functionalities of SauceDemo are working correctly  
- Identify defects early in the testing cycle  
- Maintain a structured and traceable testing workflow  

## 📌 Conclusion

The Test Plan provides a structured approach to testing, ensuring that all functionalities are validated efficiently.

By combining test management through Kiwi TCMS with automation using Selenium and Pytest, this project demonstrates a complete and professional QA workflow.
