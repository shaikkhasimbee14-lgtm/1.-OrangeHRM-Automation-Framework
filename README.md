# 1.-OrangeHRM-Automation-Framework
An end-to-end test automation framework built with Robot Framework and SeleniumLibrary for automating OrangeHRM workflows. Includes automated login, employee management, form validation, and logout test scenarios with reusable XPath locators.

# OrangeHRM Robot Framework Automation

This project is an end-to-end test automation framework built using **Robot Framework** and **SeleniumLibrary** to automate the OrangeHRM demo application. The automation covers user authentication, navigation, employee management, form handling, and user session validation.

## Project Features

* Automated login functionality with valid credentials
* Browser initialization and window management
* Navigation through OrangeHRM dashboard
* Access Admin module
* Navigate to PIM (Personnel Information Management) module
* Add new employee workflow
* Enter employee personal details:

  * First Name
  * Middle Name
  * Last Name
  * Employee ID
* Submit employee information
* Validate employee creation flow
* Handle user profile dropdown
* Perform logout functionality
* Uses XPath-based element identification
* Implements explicit waits for better element handling

## Technologies Used

* Robot Framework
* SeleniumLibrary
* Python
* Selenium WebDriver
* Google Chrome Browser

## Project Structure

OrangeHRM-RobotFramework/
│
├── tests/
│   └── orangehrm.robot
│
├── README.md
├── requirements.txt
└── .gitignore

## Installation

Install the required dependencies:

```bash
pip install robotframework
pip install robotframework-seleniumlibrary
pip install selenium
```

## Run Automation Test

Execute the Robot Framework test:

```bash
robot tests/orangehrm.robot
```

## Test Scenario Flow

1. Launch Chrome browser
2. Open OrangeHRM application
3. Login using Admin credentials
4. Navigate to Admin section
5. Open PIM module
6. Select Add Employee
7. Enter employee details
8. Save employee information
9. Open user profile menu
10. Logout from application

## Application Under Test

OrangeHRM Demo Application:

https://opensource-demo.orangehrmlive.com

## Author
Created by **Shaik Khasim Bee**  
Automation project created using Robot Framework and SeleniumLibrary.
