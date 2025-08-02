# Janitri Login Automation ✅

This is a simple project that automates the login process for Janitri’s website using **Selenium WebDriver** and **TestNG** in Java. I followed the **Page Object Model (POM)** to keep the code clean and maintainable.

## 🔧 Tools & Tech Used
- Java
- Selenium WebDriver
- TestNG
- Maven
- VS Code
## 📁 Project Structure
JanitriLoginAutomation/
|___ pom.xml
├── testing.xml # TestNG suite file
├── src/
│ ├── pages/ # Contains page classes like LoginPage.java
│ └── tests/ # Test cases like LoginPageTests.java
| |__ base / # BaseTest.java
 ## 🚀 How to Run It
You can either:
- Run the `testing.xml` file using TestNG plugin from your IDE
- Or run this from terminal (after installing Maven):
  ```bash
  mvn clean test
