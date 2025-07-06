# 🧪 Data-Driven Automation Framework

This is a **data-driven automation testing framework** built using **Selenium WebDriver**, **Java**, **TestNG**, and **Maven**. The framework is designed for practicing real-world test scenarios with a focus on maintainability, reusability, and scalability.

---

## 📌 Tech Stack

- **Language:** Java  
- **Automation Tool:** Selenium WebDriver  
- **Test Framework:** TestNG  
- **Build Tool:** Maven  
- **Data Source:** Excel (Apache POI)  
- **Design Pattern:** Page Object Model (POM)  
- **Logging & Reports:** Log4j, TestNG Reports  
- **Browser Support:** Chrome, Firefox (extendable)  

---

## 🔧 Framework Features

- 🗂️ **Page Object Model (POM)** for better code organization  
- 📊 **Data-Driven Testing** using Excel files  
- 🧪 **TestNG** for test management and reporting  
- 🔄 **Cross-Browser Testing** capability  
- 📷 **Screenshot Capture** on failure  
- 🧰 **Reusable Utility Classes** for common actions  
- 🧱 Easy to integrate with **CI/CD tools** like Jenkins

---

## 📁 Project Structure

```
project-root/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       ├── base/              # Base classes (WebDriver setup, utilities)
│   │       ├── pages/             # Page Object classes
│   │       ├── utils/             # Excel reading, waits, screenshot helpers
│   │       └── config/            # Config reader classes
│   └── test/
│       └── java/
│           └── tests/             # TestNG test classes
│
├── testdata/                      # Excel files for input data
├── pom.xml                        # Maven configuration
└── testng.xml                     # Test suite configuration
```

---

## ▶️ How to Run Tests

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. **Import into IDE (IntelliJ or Eclipse)**

3. **Update `testdata/` Excel file** as needed

4. **Run using Maven:**
   ```bash
   mvn clean test
   ```

---

## 📌 TestNG XML Example

```xml
<suite name="Sample Suite">
  <test name="Login Test">
    <classes>
      <class name="tests.LoginTest" />
    </classes>
  </test>
</suite>
```

---

## 🔐 Author

**Shailesh Pokharkar**  
Automation QA | 5+ years experience in Manual + Automation + API Testing

---

## 📄 License

This project is for educational and personal practice use. You are free to use, modify, and extend it.
