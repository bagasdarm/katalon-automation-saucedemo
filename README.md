# katalon-automation-saucedemo
Automated UI Testing portfolio for SauceDemo (Swag Labs) e-commerce website using Katalon Studio.

# SauceDemo - UI Automation Testing

### Project Overview
This repository contains an automated UI testing project for **SauceDemo (Swag Labs)**, a dummy e-commerce website designed for testing purposes. The automation scripts are built to verify the core functionalities of the web application, ensuring a smooth user experience from authentication to the checkout process.

### Tools & Technology
- **Automation Tool:** Katalon Studio
- **Language:** Groovy / Java
- **Target Application:** Web Browser (saucedemo.com)

### Test Documentation
The detailed manual Test Cases and Test Scenarios used as the foundation for this automation project can be accessed here:
- **[View Test Cases on Google Sheets](https://docs.google.com/spreadsheets/d/1BbPIHQTw9bwnW7_cmP1T2AFnN_V_40LOsdKapl9RFQw/edit?usp=sharing)**

*(You can also find the exported PDF/Excel version of the test cases in the `Docs` folder of this repository).*

### Automated Scenarios Covered
This automation project covers the following critical flows:
1. **Authentication (Login):**
   - Successful login with valid credentials.
   - Failed login with invalid credentials.
   - Login attempt with a locked-out user.
2. **Product & Cart Management:**
   - Adding single and multiple products to the cart.
   - Removing products from the cart.
   - Verifying cart badge counter updates.
3. **Checkout Process:**
   - Filling out buyer information.
   - Verifying the final order summary.
   - Completing the transaction and verifying the success message.

### How to Run This Project
1. Clone this repository to your local machine:
   `git clone https://github.com/bagasdarm/katalon-automation-saucedemo.git`
2. Open **Katalon Studio**.
3. Click on `File > Open Project` and select the cloned folder.
4. Open the `Test Suites` folder and execute the desired test suite.
5. Select your preferred browser (Chrome/Firefox) to run the test.

---
*This project is part of my Software Quality Assurance portfolio.*
