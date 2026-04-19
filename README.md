# Test Case Management System

## Test Case Planning – SauceDemo Web App Functional Testing

The test cases in this project are designed based on the SauceDemo Web App Testing repository:  
[SauceDemo Web App Testing](https://github.com/tahsinnahmed/SauceDemo-Web-App-Testing.git)

---

## What is a Test Plan?

A Test Plan is a formal document that defines the scope, objectives, strategy, resources, and schedule of testing activities for a software project. It serves as a blueprint to ensure that all testing efforts are well-structured, organized, and aligned with project requirements.

In test management tools like **Kiwi TCMS**, a Test Plan represents a collection of test cases grouped to validate a specific feature, module, or the entire application.

---

## Purpose of the Test Plan

The Test Plan helps to:

- Define what needs to be tested  
- Outline testing strategy and approach  
- Organize test cases into a structured flow  
- Assign responsibilities and resources  
- Track testing progress and results  
- Ensure complete coverage of application functionality  

---

## Test Plan in This Project

For the **SauceDemo Web App Testing** project, the Test Plan includes all functional test scenarios related to the application.

### Test Plan Name:
**SauceDemo Web App Testing**

---

## Test Case Results

The following table presents the execution results of all test cases performed for the SauceDemo Web Application. It includes test case ID, description, status, priority, environment, and test data used during execution.

| Test Case ID | Test Case Description                                   | Status | Priority |   Category  |    Author    |    Tester    |
|-------------|----------------------------------------------------------|--------|----------|-------------|--------------|--------------|
| TC-40041    | Valid login with correct credentials                     | Pass   | High     | --default-- |  hack4tahsin |  hack4tahsin |
| TC-40042    | Invalid login with wrong credentials                     | Pass   | High     | --default-- |  hack4tahsin |  hack4tahsin |
| TC-40043    | Add product to cart from inventory page                  | Pass   | High     | --default-- |  hack4tahsin |  hack4tahsin |
| TC-40044    | View added products in cart                              | Pass   | High     | --default-- |  hack4tahsin |  hack4tahsin |
| TC-40045    | Proceed to checkout from cart                            | Failed | Medium   | --default-- |  hack4tahsin |  hack4tahsin |

### Summary

- Total Test Cases: **5**  
- Passed: **4**  
- Failed: **1**  
- Pass Rate: **80%**

This test execution demonstrates functional validation of the SauceDemo application using structured test cases with clear pass/fail reporting and traceable test data.

<img width="1860" height="892" alt="Test Cases" src="https://github.com/user-attachments/assets/90d5bd11-21ac-4de4-8a45-2d52392bbaa8" />

---

## Scope of Testing

The Test Plan covers the following modules:

### Login Functionality
- Valid login  
- Invalid login  

<p align="center">
<img width="900" alt="TC-01" src="https://github.com/user-attachments/assets/f863fdbe-0801-4c97-a957-28afcb19eae7" />
<img width="900" alt="TC-02" src="https://github.com/user-attachments/assets/ae6d10c0-f8da-45b3-afab-22efc2041fc3" />
</p>

---

### Inventory Management
- View products  
- Add items to cart  

<p align="center">
<img width="900" alt="TC-03" src="https://github.com/user-attachments/assets/077c89ac-90b7-4187-85c2-18446bcc6c0b" />
</p>

---

### Cart Functionality
- View cart items  
- Navigate to checkout  

<p align="center">
<img width="900" alt="TC-04" src="https://github.com/user-attachments/assets/66b1fbbf-5f36-4899-a78d-57cc697acdc1" />
</p>

---

### Checkout Process
- Enter user information  
- Complete purchase  

<p align="center">
<img width="1903" height="886" alt="TC-05" src="https://github.com/user-attachments/assets/93dccdee-264b-44ff-9297-2857c9b51507" />
</p>

---

## Test Strategy

- **Type of Testing:** Functional Testing  
- **Approach:**
  - Manual test case design using Kiwi TCMS  
  - Automated test execution using Selenium and Pytest  
- **Design Pattern:** Page Object Model (POM)  
- **Test Data:** JSON-based input data  

---

## Test Environment

- **Application:** SauceDemo Web Application  
- **URL:** https://www.saucedemo.com/  
- **Browser:** Google Chrome  
- **Automation Tool:** Selenium WebDriver  
- **Test Framework:** Pytest  
- **Reporting Tools:** Allure Reports, Excel (openpyxl)  

---

## Test Execution

- Test cases are executed using Pytest automation scripts  
- Results are:
  - Visualized using Allure Reports  
  - Logged into Excel for defect tracking  
  - Maintained in Kiwi TCMS for traceability  

---

## Defect Management

Failed test cases are logged in Excel for tracking and analysis.

Each defect includes:

- Bug ID  
- Test Case Name  
- Error Description  
- Status  

<p align="center">
<img width="900" alt="Defect Tracking" src="https://github.com/user-attachments/assets/4a339863-4fc8-4ce5-bc74-e88113112c43" />
</p>

---

## Objectives

- Ensure all core functionalities of the SauceDemo application work correctly  
- Identify defects early in the testing cycle  
- Maintain a structured and traceable testing workflow  

---

## Conclusion

The Test Plan provides a structured and systematic approach to software testing, ensuring complete validation of application functionality.

By combining test management using **Kiwi TCMS** with automation using **Selenium and Pytest**, this project demonstrates a complete and professional QA workflow.
