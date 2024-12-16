**Project Overview:** 

This project demonstrates and end-to-end UI test automation framework for testing the Open Cart e-commerce application. The framework is implemented using Selenium 4.x, Java, & TestNG. It is designed for
robust and scalable automated testing of web applications.






**Features:**

*Page Object Model (POM): Clean separation of test scripts and page objects for better maintainability.

*Custom WebDriver Event Listeners: Enhanced logging and reporting of browser interactions.

*Dynamic Wait Strategies: Efficient use of explicit and fluent waits to handle dynamic elements.

*Data-Driven Testing: Utilizes CSV data providers for test parameterization.

*Parallel Execution: Leverages TestNG for executing tests in parallel to reduce execution time.

*Cross-Browser Testing: Supports testing on Chrome, Firefox, and Edge browsers.

*Detailed Reporting: Generates test execution reports using ExtentReports and Allure Reports.

*Custom Exception Handling: Retry mechanisms for flaky tests and enhanced failure management.

*Screenshots on Failures: Captures screenshots automatically for failed tests.

*Reusable Components: Includes libraries for common UI elements and actions.

*Integration with CI/CD: Configured for Jenkins to enable continuous testing.






**Tech Stack:**

1.IDE - Eclipse

2.Language - Java

3.Maven - Build Tool

4.TestNG - Unit testing framework

5.Design Pattern - Page Object Model (POM)

6.Log4j - Logging

7.Extent & Allure Reports - Reporting

8.CI/CD Pipeline using Jenkins

9.Selenium Grid setup

10.Selenoid Docker grid Execution

11.AWS Cloud to run the test cases on cloud



    

**Infrastructure Setup:**


Selenium Grid and Selenoid Integration:

*Distributed Testing: Implements Selenium Grid & Selenoid for executing test across multiple nodes.

*Dockerized Environment: Uses Docker containers for browser nodes.

*Auto-Scaling: Automatically scales based on test load.



**Prerequisites:**

1.Java JDK 11 or higher.

2.Maven

3.Selenium WebDriver

4.TestNG

5.Docker(for Selenium Grid and Selenoid Setup)

6.Browsers: Chrome, Firefox, Edge



**Installation and Setup:**


1.Clone the repository:

git clone https://github.com/veena444/E2EUIAutomationProject-OpenCart.git

2.Navigate to the project directory:

cd E2EUIAutomationProject-OpenCart

3.Install dependencies using Maven:

mvn clean install



**Running Tests:**

###Local Execution:

1.Update the testng.xml file to specify test configurations.

2.Run tests using maven:

mvn test


###Parallel Execution:

Enable parallel execution in the testng.xml file under <suite> tag:

<suite name="TestSuite" parallel="tests" thread-count="4">


###CI/CD Integration:

1.Configure Jenkins with this project.

2.Add a Jenkins pipeline for executing tests.

3.Ensure Docker & Selenoid are installed on the CI server for distributed testing.



**Reporting:**

ExtentReports: HTML-based reports for detailed test execution results.

Allure Reports: Graphical and interactive reports for better analysis.

Screenshots: Automatically attached to reports for failed test cases.



    










