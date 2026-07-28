# 🧪 Software Testing Projects

A collection of manual software testing artifacts — test case reports, defect/bug tracking reports, and QA dashboards — created to demonstrate practical QA documentation and testing skills on real (sample) application features.

This repository is intended for students, beginners, and recruiters who want to see real-world software testing documentation in action.

---

## 📂 Repository Structure

```
SoftwareTesting_Projects/
│
├── ChatApp/
│   ├── test_case_report.xlsx           # Test case suite for a chat application
│   └── Defect_Tracking_Report.xlsx      # Defect log & QA defect dashboard
│
└── README.md
```

> Each top-level folder represents a project under test (currently: **ChatApp**). More project folders will be added over time.

---

## 💬 Project: ChatApp

Manual QA testing performed on a sample chat application, covering registration, login, and core chat functionality.

### `test_case_report.xlsx`
Contains a **Test Cases** sheet and a **Dashboard** sheet.

Each test case includes:
- Test Case ID
- Test Scenario
- Module / Feature
- Priority
- Pre-conditions
- Test Steps
- Test Data
- Expected Result
- Actual Result
- Status (Pass/Fail)
- Remarks

Covers scenarios such as:
- Registration with valid details / existing email
- Login with valid/invalid credentials and expired sessions
- Core chat feature flows

The **Dashboard** sheet summarizes test execution results and module-level metrics.

### `Defect_Tracking_Report.xlsx`
Contains a **Defect Log** sheet and a **Defect Dashboard** sheet.

Each logged defect includes:
- Defect ID
- Defect Title / Summary
- Module / Feature
- Environment
- Severity
- Priority
- Steps to Reproduce
- Expected Result
- Actual Result
- Status (Fixed/Open/etc.)

Example defects tracked:
- Login failing to handle abrupt JWT token expiration
- Duplicate email registration allowed under high-latency race conditions

The **Defect Dashboard** sheet summarizes defect metrics, severity breakdown, and resolution status.

---

## 🛠 Tools Used

- Microsoft Excel (test case & defect tracking spreadsheets, dashboards)
- Manual Testing techniques
- Git & GitHub

---

## 🎯 Objectives

- Practice manual testing and QA documentation
- Learn structured test case design
- Practice defect/bug reporting and tracking
- Build a professional QA portfolio

---

## 📈 Skills Demonstrated

- Manual Testing
- Functional Testing
- Test Case Design
- Bug Reporting & Defect Tracking
- QA Dashboards & Reporting
- Requirement Analysis
- Documentation

---

## 🚀 Future Improvements

- Additional project folders with more application testing artifacts
- Test Plans and Requirement Traceability Matrix (RTM)
- Automation testing (Selenium / Cypress / Playwright)
- API Testing with Postman
- CI/CD testing pipeline integration

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

Feel free to:
- Fork this repository
- Create a new branch
- Commit your changes
- Open a Pull Request

---

## 📄 License

This repository is created for educational and portfolio purposes.

---

## 👨‍💻 Author

**Prem Kathayat**
- Final Year BCA Student
- MERN Stack Developer & Software Testing Enthusiast
- Passionate about Quality Assurance and Software Development

---

⭐ If you find this repository helpful, don't forget to **Star** it.