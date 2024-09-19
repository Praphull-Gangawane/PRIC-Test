# PRIC-Test
# Locked Message Automation Test

This repository contains automated test scripts written in Java using Selenium WebDriver for testing the login functionality (with mobile number and OTP verification) and locked message features of the web application [https://app.thepric.com/priclogin].

## Project Setup

### Prerequisites:
- Java JDK 8 or higher
- Maven
- Chrome browser

### How to Run:
1. Clone the repository:
    ```bash
    git clone https://github.com/Praphull-Gangawane/PRIC-Test.git
    ```
2. Navigate to the project folder:
    ```bash
    cd test-script
    ```
3. Run the tests using Maven:
    ```bash
    mvn test
    ```

## Test Cases:
- **LoginTests.java**: Valid and invalid login scenarios using mobile number and OTP verification.
- **LockedMessageTests.java**: Creating, deleting, and verifying locked messages.

## Tools Used:
- Selenium WebDriver
- TestNG
- WebDriverManager

## Setup and Prerequisites:
 **Tools and Libraries Needed**:
- Java Development Kit (JDK) 8 or later
- Maven (for project build and dependencies)
- Selenium WebDriver (for browser automation)
- TestNG (for test execution and reporting)
  
 **Libraries to Include in the pom.xml**:
- To get started, create a Maven project and add the following dependencies in your pom.xml:

 ```
<dependencies>
    <!-- Selenium Java Dependency -->
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.1.0</version>
    </dependency>

    <!-- TestNG for testing -->
    <dependency>
        <groupId>org.testng</groupId>
        <artifactId>testng</artifactId>
        <version>7.4.0</version>
        <scope>test</scope>
    </dependency>

    <!-- WebDriverManager for handling browser binaries -->
    <dependency>
        <groupId>io.github.bonigarcia</groupId>
        <artifactId>webdrivermanager</artifactId>
        <version>5.0.3</version>
    </dependency>
</dependencies>
