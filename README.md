Selenium TestNG E-Commerce Framework
GitHub Actions GitHub Actions: https://github.com/vijaya1123/SeleniumEcommerceFrmework/actions

🚀 Overview
Industrial-standard Selenium TestNG hybrid automation framework for SauceDemo with data-driven testing, parallel execution, CI/CD pipeline, and enterprise-level design patterns.

Repository: https://github.com/vijaya1123/SeleniumEcommerceFrmework.git

📊 Allure Report
View the latest test results: Allure Report

📋 Features
Hybrid Framework Architecture: Page Object Model (POM) + Data-Driven Testing
Thread-Safe WebDriver: ThreadLocal implementation for parallel execution
Cross-Browser Support: Chrome and Edge browsers
Data-Driven Testing: CSV-based test data management
Dynamic Test Data: Random data generation utilities
Comprehensive Logging: Log4j2 integration
Rich Reporting: Allure Reports with screenshots
CI/CD Ready: GitHub Actions workflow with automatic deployment
Retry Mechanism: Automatic retry for failed tests
Custom Listeners: TestNG listeners for enhanced reporting
GitHub Pages: Automated Allure report publishing
🏗️ Project Structure
selenium-testng-ecommerce-framework/
├── src/
│   ├── main/java/com/seleniumui/
│   │   ├── base/           # Base classes (BasePage, BaseTest, DriverFactory)
│   │   ├── pages/          # Page Object classes
│   │   ├── utils/          # Utility classes
│   │   └── listeners/      # TestNG listeners
│   └── test/java/com/seleniumui/tests/
│       ├── LoginTest.java
│       ├── ProductTest.java
│       ├── CheckoutTest.java
│       └── SessionTest.java
├── .github/workflows/      # CI/CD configuration
├── testng.xml              # TestNG configuration
└── pom.xml                 # Maven configuration
🛠️ Prerequisites
Java 11 or higher
Maven 3.6+
Chrome or Edge browser
🚀 Quick Start
Clone the repository
git clone https://github.com/vijaya1123/SeleniumEcommerceFrmework.git
Run all tests
mvn clean test
Run tests in headed mode (visible browser)
mvn clean test -Dheadless=false
Run smoke tests only
mvn clean test -Psmoke
Generate Allure Report
mvn allure:report
Open Allure Report
mvn allure:serve
📦 Dependencies
Dependency	Version	Purpose
Selenium	4.18.1	Web automation
TestNG	7.9.0	Test framework
WebDriverManager	5.7.0	Browser driver management
Log4j2	2.23.0	Logging
Allure TestNG	2.25.0	Reporting
OpenCSV	5.9	CSV data handling
🧪 Test Modules
LoginTest: Valid login scenarios
ProductTest: Add to cart, remove, sorting functionality
CheckoutTest: Complete checkout flow with dynamic data
SessionTest: Session validation and security tests
🔄 CI/CD Pipeline
The project includes GitHub Actions workflow that:

Runs tests on every push/PR
Generates Allure Report
Deploys report to GitHub Pages
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
