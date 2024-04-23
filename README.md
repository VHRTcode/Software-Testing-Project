# Software-Testing-Project

<details>
<summary><font color="#1589F0"><b>Software Testing Project Information</b></font></summary>


# Software Testing Live Project (Theory)

## 1. Project Information

- **Domain:** Ecommerce
- **Sub Domain:** B2C (Business to Customer)
- **Application:** Online Shopping
- **Application Type:** Public Web Application (Internet Application)
- **Development Technologies:** LAMP (Linux, Apache, MySQL, PHP)

## 2. Project Overview

### i. Admin Interface/Server-side
- Application Master Data (Add/Edit/Delete)
- Maintenance (User management, Operations management, etc.)

### ii. User Interface/Client-side
- To perform specified Business operations

## 3. Stakeholders of the Project

- Project Leader
- Senior Management
- Project Team Members
- Project Customer
- Project Testers
- Subcontractors, Consultants, etc.

## 4. Interfaces of the Project/AUT

### i. Admin Interface:
- URL: [Admin Interface](http://gcreddy.com/project/admin/)
- Username: gcreddy
- Password: Temp@2020

### ii. User Interface:
- URL: [User Interface](http://gcreddy.com/project/)

## 5. Features to be Tested in Admin Interface

- Launch Application
- Login to Admin Interface
- Redirecting Operation from Admin to User Interface
- Add/Edit/Delete Manufacturer
- Add/Edit/Delete Category
- Add/Edit/Delete Product
- Add/Edit/Delete/Set as Default Currency
- Reports (User, Product, etc.)

## 6. Features to be Tested in User Interface

- Launch Application
- View Products
- Search Products
- Advanced Search
- Customer Registration
- Customer Login
- Buy Products (Login, Choose products, Update Quantity, Delete Products, Change Details, Select Payment Option, Checkout...)
- Track Order status

## 7. Derive Sanity Test Scenarios for Admin Interface

- Launch Application
- Verify required elements availability in the Admin interface home page/login page
- Verify Admin Login with valid username and password
- Verify required elements availability on the Index page
- Add Manufacturer
- Add Category
- Add Product
- Add Currency

## 8. Derive Sanity Test Scenarios for User Interface

- Verify the Launch of User Interface with valid URL
- Verify required elements availability in the home page
- Verify Customer Registration with valid data
- Verify Customer Login
- Verify Shopping Cart
- Verify Checkout
- Verify Log Off

## 9. Derive Comprehensive (All Possible) Test Cases for Admin Interface

- Verify Launch Application with valid URL
- Verify all elements availability in the Admin interface home page/login page
- Verify "Redirect" functionality from Admin to User Interface before Login
- Verify Admin Login with various scenarios (valid/invalid username/password, blank fields, locking functionality)
- Verify all elements available on the Index page
- Add/Edit/Delete/Move Manufacturer, Category, Product, Currency
- Set Default Currency
- Verify Customer and Product Reports
- Verify "Logoff"

## 10. Derive Comprehensive (All Possible) Test Cases for User Interface

- Verify the Launch of User Interface with valid URL
- Verify all elements available on the home page
- Verify Customer Registration with various scenarios (valid/invalid data, existing email)
- Verify Customer Login with valid email address and password
- Verify Shopping Cart functionality with various scenarios (before selecting any product, after selecting products, updating quantity, removing products)
- Verify Checkout process with various scenarios (before selecting any product, after selecting products, address change, adding comments, selecting payment option, order confirmation)
- Verify "Logoff"


  
</details>


<details>
<summary><b>Test Plan</b></summary>

## Objective
The objective of this test plan is to ensure thorough testing of the Online Shopping application, covering both the Admin Interface and User Interface, to validate its functionality, usability, and performance.

## Scope
This test plan will encompass testing of all features and functionalities as outlined in the project overview, including but not limited to:
- Admin Interface features such as adding/editing/deleting manufacturers, categories, products, and currencies.
- User Interface features such as product browsing, search, registration, login, shopping cart management, checkout, and order tracking.

## Inclusions
- Functional testing
- Usability testing
- Performance testing
- Security testing
- Compatibility testing

## Test Environments
<details>
<summary>Details</summary>

| Environment         | Details                                          |
|---------------------|--------------------------------------------------|
| Browser             | Chrome, Firefox, Safari                          |
| Operating Systems   | Windows, macOS, Linux                            |
| Devices             | Desktop, Laptop, Mobile (iOS, Android)           |
| Development Environment | LAMP stack (Linux, Apache, MySQL, PHP)         |
</details>

## Defect Reporting Procedure
- Defects will be reported using the company's designated defect tracking tool.
- Each defect report will include a detailed description, steps to reproduce, severity, and priority.

## Test Strategy
- A combination of manual and automated testing will be employed.
- Test cases will cover positive and negative scenarios, edge cases, and stress testing.
- Regression testing will be performed after each build/release.

## Test Schedule
- Test preparation and planning: [Start Date] - [End Date]
- Test execution: [Start Date] - [End Date]
- Defect reporting and tracking: Throughout the testing phase
- Test closure: Upon completion of testing activities

## Test Deliverables
- Test plan document
- Test cases
- Test execution reports
- Defect reports

## Entry and Exit Criteria
<details>
<summary>Entry Criteria</summary>

- Completion of application development
- Availability of test environment
- Test data preparation
</details>

<details>
<summary>Exit Criteria</summary>

- Successful completion of all test cases
- Defect closure rate above [Threshold]
- Approval from project stakeholders
</details>

## Test Execution
<details>
<summary>Entry Criteria</summary>

- Completion of test environment setup
- Availability of test data
- Approval of test plan
</details>

<details>
<summary>Exit Criteria</summary>

- Completion of all test cases
- Generation of test execution reports
- Approval of test execution results
</details>

## Test Closure
<details>
<summary>Entry Criteria</summary>

- Completion of all test execution activities
- Review and approval of test results
- Closure of all defects
</details>

<details>
<summary>Exit Criteria</summary>

- Sign-off from project stakeholders
- Archiving of test documentation and artifacts
</details>

## Tools
- Defect Tracking: [Tool Name]
- Test Management: [Tool Name]
- Automation: [Tool Name]

## Risks and Mitigations
- **Risk:** Insufficient test coverage
  - **Mitigation:** Regular reviews of test coverage and test plan updates.
- **Risk:** Limited resources for testing
  - **Mitigation:** Prioritize testing activities and consider resource allocation adjustments.

## Approvals
This test plan is approved by:

Project Manager: [Name]  
Date: [Date]
</details>

<details>
<summary>Test Case 1: Verify the Launch of Admin Interface</summary>

**Test Steps**:
1. Launch the browser.
2. Capture the page title.

**Expected Result**: The page title is "osCommerce Online Merchant Administration Tool".

</details>

<details>
<summary>Test Case 2: Verify Mandatory Elements Availability in Admin Interface Home Page</summary>

**Test Steps**:
1. Launch the browser.
2. Check the availability of "Create an Account", "Login", and "Shopping Cart" links.

</details>

<details>
<summary>Test Case 3: Page Redirect Functionality (From Admin to User Interface) Before Login</summary>

**Test Steps**:
1. Launch the browser.
2. Navigate to the Admin login page.
3. Click the "Online CataLog" link.
4. Capture the current URL.

**Expected URL**: http://gcreddy.com/project/

</details>

<details>
<summary>Test Case 4: Verify Admin Login with Valid Data</summary>

**Test Steps**:
1. Launch the browser.
2. Navigate to the Admin login page.
3. Enter valid username and password.
4. Click the "Login" button.
5. Capture the current URL.
6. Check the availability of the "Logoff" link.

**Expected Result**: 
- URL: http://gcreddy.com/project/admin/index.php/
- "Logoff" link is available.

</details>

<details>
<summary>Test Case 5: Verify Admin Login with Invalid Data</summary>

**Test Steps**:
1. Launch the browser.
2. Navigate to the Admin login page.
3. Enter invalid username and password.
4. Click the "Login" button.
5. Capture the error message displayed on the screen.

**Expected Message**: "Error: Invalid administrator login attempt."

</details>

<details>
<summary>Test Case 6: Verify Admin Login Locking Functionality</summary>

**Test Steps**:
1. Launch the browser.
2. Navigate to the Admin login page.
3. Enter incorrect username and password for four times.
4. Capture the error messages displayed.

**Expected Results**: 
- 1st to 3rd Iterations: "Error: Invalid administrator login attempt"
- 4th Iteration: "Error: The maximum number of login attempts has been reached. Please try again in 5 minutes."

</details>

<details>
  <summary><b> Test Execution </b></summary>
  # Test Execution Plan

## 1. Test Environment Setup
- **Hardware Configuration**: Ensure access to computers or devices with internet connectivity.
- **Software Configuration**:
  - Web Browsers: Chrome, Firefox, Safari
  - Operating Systems: Windows, macOS, Linux
  - Development Environment: LAMP stack (Linux, Apache, MySQL, PHP)
  - Testing Tools: Defect tracking tool, Test management tool

## 2. Execute Test Cases
- Refer to the test plan for the list of test cases to be executed.
- Follow the steps outlined in each test case meticulously.
- Ensure adherence to the predefined test data and expected results.

## 3. Defect Logging
- Log any defects or issues encountered during test execution promptly.
- Provide detailed descriptions of each defect, including steps to reproduce and observed behavior.
- Assign a severity level to each defect based on its impact on the system.

## 4. Capture Evidence
- Capture screenshots or videos as evidence for bug reports where applicable.
- Screenshots should highlight the issue and provide context to aid in understanding and resolution.
- Videos can be used to demonstrate complex issues or scenarios that cannot be adequately conveyed through screenshots.

## 5. Retest Resolved Defects
- After defects have been resolved by the development team, retest the affected functionality to ensure that the fixes have been implemented correctly.
- Follow the same test steps as initially executed during the defect discovery phase.
- Verify that the previously observed issues have been resolved and that the functionality behaves as expected.

## 6. Documentation
- Document the test execution process thoroughly, including:
  - Test case execution results
  - Defect logs with status updates
  - Screenshots or videos of captured evidence
- Update the test documentation with any changes or updates based on the test execution outcomes.

</details>


<details>
<summary>Regression Testing Plan</summary>

## 1. Purpose
The purpose of regression testing is to ensure that bug fixes or new features do not introduce any new issues and to verify the overall stability and integrity of the e-commerce website.

## 2. Approach
- Execute a subset of test cases covering critical functionalities.
- Focus on areas most impacted by recent changes or bug fixes.
- Prioritize test cases based on their relevance to the core functionalities of the application.

## 3. Test Cases Selection
- Select a subset of test cases from the existing test suite that cover critical functionalities such as user registration, login, product browsing, checkout, etc.
- Include test cases that have a high likelihood of being impacted by recent changes or bug fixes.
- Prioritize test cases based on their importance to the overall functionality and user experience of the e-commerce website.

## 4. Execution Process
- Execute the selected test cases in the test environment configured for regression testing.
- Follow the predefined test steps and expected results for each test case.
- Log any defects or issues encountered during regression testing.
- Ensure thorough coverage of critical functionalities to verify the stability and integrity of the e-commerce website.

## 5. Documentation
- Document the regression testing process, including:
  - Test cases executed
  - Test results and outcomes
  - Defects logged and their status
- Update the test documentation with any changes or updates based on the regression testing outcomes.

## 6. Frequency
- Regression testing should be performed:
  - After bug fixes or code changes are implemented.
  - Before major releases or deployments.
  - Periodically to ensure the ongoing stability of the e-commerce website.

</details>


<details>
<summary>5. Usability Testing</summary>

### Purpose:
Evaluate the website's user-friendliness and ease of navigation.

### Activities:
- Validate the website's responsiveness across different devices and screen sizes.
- Check for consistent branding, proper labeling, and intuitive user interfaces.
- Gather user feedback to identify areas of improvement.

### Approach:
- Conduct usability testing with representative users.
- Use usability testing tools to analyze user interactions and behavior.
- Implement changes based on user feedback to enhance the overall user experience.

</details>

<details>
<summary>6. Performance Testing</summary>

### Purpose:
Measure the website's performance under different load conditions.

### Activities:
- Conduct load testing to determine the system's capacity and response times.
- Monitor resource utilization to identify bottlenecks or performance issues.
- Ensure the website can handle peak traffic without significant slowdowns.

### Approach:
- Use performance testing tools to simulate realistic user loads.
- Analyze performance metrics such as response time, throughput, and error rates.
- Optimize system resources and configurations to improve performance.

</details>

<details>
<summary>7. Security Testing</summary>

### Purpose:
Assess the website's security measures, including authentication and authorization mechanisms.

### Activities:
- Test for vulnerabilities such as SQL injection, cross-site scripting (XSS), and session management flaws.
- Verify secure communication using SSL/TLS protocols.
- Ensure sensitive user data is properly protected and encrypted.

### Approach:
- Use security testing tools to identify and mitigate potential vulnerabilities.
- Implement security best practices such as input validation and access controls.
- Conduct regular security audits to maintain a secure website environment.

</details>

<details>
<summary>8. Test Summary and Reporting</summary>

### Purpose:
Document the test results, including test execution status, defects found, and their severity.

### Activities:
- Provide a summary of the overall test coverage and test completion metrics.
- Prepare a final test report with recommendations for improvements.
- Conduct a test closure meeting to discuss the project's outcomes and lessons learned.

### Approach:
- Use a test management tool to track test execution and defect status.
- Generate test reports to communicate the results to stakeholders.
- Document lessons learned and areas for improvement to inform future testing efforts.

</details>

