## UI Automation – SauceDemo

This project includes a UI automation test that validates the core purchase flow on SauceDemo using Selenium with Java.

### Test Scenario
The automated test performs the following steps:

1. Open SauceDemo website
2. Login with valid credentials
3. Add products to the shopping cart
4. Navigate to the cart page
5. Proceed to checkout
6. Fill in customer information
7. Complete the order
8. Validate successful checkout

### Test URL
https://www.saucedemo.com/

### Test Credentials
Username: standard_user  
Password: secret_sauce

### Tools Used
- Selenium WebDriver
- Java
- TestNG / JUnit
- Maven
- ChromeDriver

### Run Tests

```bash
mvn clean test
