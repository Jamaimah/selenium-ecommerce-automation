# 📊 Selenium E-commerce Automation Suite

> 📌 Final project from internal Selenium WebDriver training — developed as part of my transition into a Java QA Automation Engineer role.

## 🚀 Project Overview

This automation suite tests core functionalities of a **demo e-commerce platform** using industry-standard tools and frameworks. It includes test coverage for account creation, login, address management, wishlist, and cart functionality.

👌 The project applies real-world test automation design principles using Java, Selenium, and Allure.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Java** | Programming Language |
| **Maven** | Build & Dependency Management |
| **JUnit 5** | Test Framework |
| **Selenium WebDriver** | Browser Automation |
| **Allure Reports** | Test Reporting |
| **Faker** | Dummy Test Data |
| **Lombok** (optional) | Code Simplification |

---

## 📂 Project Highlights

- ✅ Page Object Model + Page Factory design
- ✅ Singleton WebDriver for optimized execution
- ✅ Configurable browser execution (Chrome / Firefox)
- ✅ Screenshot capture on failure with metadata (timestamp, browser, OS)
- ✅ Compatibility with Selenium Grid / Docker / SauceLabs (param-based switch)
- ✅ Easily extensible for new test cases

---

## 🧪 Automated Test Scenarios

| Test ID | Description | URL |
|--------|-------------|-----|
| **AP-1** | Verify account registration | [`/customer/account/create/`](https://magento.softwaretestingboard.com/customer/account/create/) |
| **AP-2** | Verify login functionality | [`/`](https://magento.softwaretestingboard.com) |
| **AP-3** | Verify address addition | [`/customer/address/index/`](https://magento.softwaretestingboard.com/customer/address/index/) |
| **AP-4** | Verify wishlist feature | Product page |
| **AP-5** | Verify add to cart & subtotal | Product + cart pages |

---

## 🧪 Test Execution

- ✔ Run test classes individually — each opens a new browser instance
- ✔ Supports Chrome and Firefox via WebDriverManager
- ✔ Switch test execution (local/Selenium Grid/Docker) using config params
- ✔ Allure HTML reports generated with screenshots on failure

---


## 🔄 Future Enhancements (Optional)

- CI/CD Integration with GitHub Actions or Jenkins
- Environment-based configuration management
- Data-driven testing using external `.json` or `.xml`

---

## 📌 How to Run

```bash
# Install dependencies
mvn clean install

# Run all tests
mvn test

# View reports (after test)
allure serve target/allure-results
```

---

## 🙋‍♀️ Author

**Jamaima Baig**  
📧 jamaimabaig99@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/jamaima-baig-3116381b0/) 

