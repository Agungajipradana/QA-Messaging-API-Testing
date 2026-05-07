
# 📌 QA Messaging API Testing

This repository showcases a **Quality Assurance (QA) portfolio project** focused on testing a **Messaging & CRM API system** used for customer communication and campaign management.

The project demonstrates real-world QA workflows including:

- Manual Testing
- API Testing
- Automation Testing
- Bug Reporting
- CI/CD Integration
- Test Reporting

> ⚠️ Note: All endpoints, credentials, tokens, company names, and sensitive data have been anonymized for confidentiality purposes.

---

# 🧠 Project Overview

This project simulates testing activities for a **Messaging CRM platform** that includes authentication, messaging, campaign management, user management, templates, bots, journeys, reports, and system configurations.

The repository is structured to reflect how QA engineers organize testing assets in real production environments.

---

# ✅ Features Covered

## 🔐 Authentication
- Register
- Login
- Token validation
- Unauthorized access handling

## 💬 Messaging / Chat
- Send messages
- Message validation
- Error handling
- Duplicate requests
- Edge cases

## 🏢 Companies
- Company management
- Validation scenarios

## 👥 Users & Roles
- User permissions
- Role access validation

## 📢 Campaigns
- Campaign creation
- Campaign validation

## 👤 Contacts
- Contact management
- Invalid contact handling

## 🧩 Templates
- Template validation
- Dynamic content testing

## 🤖 Bots & Flows
- Automation flow validation
- Bot trigger scenarios

## 🛣 Journeys
- User journey testing
- Workflow validation

## 📊 Reports
- Report generation
- Data validation

## ⚙️ Settings & Themes
- Configuration testing
- Theme validation

---

# 🧪 Testing Scope

## ✅ In Scope

- Functional Testing
- API Testing
- Positive Testing
- Negative Testing
- Edge Case Testing
- Authentication Testing
- Automation Testing
- Regression Testing
- CI/CD Automation

---

## ❌ Out of Scope

- Penetration Testing
- Load/Stress Testing
- Infrastructure Testing
- Mobile Testing

---

# 📂 Project Structure

```plaintext
QA-Messaging-API-Testing/
│
├── .github/
│   └── workflows/
│       └── test.yml
│
├── manual-testing/
│   ├── test-plan.md
│   ├── test-cases/
│   │   ├── TC-auth.xlsx
│   │   ├── TC-companies.xlsx
│   │   ├── TC-users-roles.xlsx
│   │   ├── TC-chat.xlsx
│   │   ├── TC-campaigns.xlsx
│   │   ├── TC-contacts.xlsx
│   │   ├── TC-templates.xlsx
│   │   ├── TC-bots-flows.xlsx
│   │   ├── TC-journeys.xlsx
│   │   ├── TC-reports.xlsx
│   │   └── TC-settings-themes.xlsx
│   │
│   └── bug-reports/
│       ├── BUG-001.md
│       └── screenshots/
│
├── api-testing/
│   ├── postman_collection.json
│   ├── environment.json
│   ├── newman-screenshot.png
│   └── README.md
│
├── automation/
│   ├── playwright/
│   │   ├── tests/
│   │   ├── helpers/
│   │   ├── pages/
│   │   ├── playwright.config.js
│   │   ├── package.json
│   │   └── README.md
│   │
│   └── selenium/
│       ├── tests/
│       ├── package.json
│       └── README.md
│
├── test-reports/
│   ├── report-sprint-1.pdf
│   ├── summary.md
│   └── screenshots/
│
└── README.md
````

---

# 📝 Manual Testing

Manual testing artifacts include:

* Test Plan
* Test Cases
* Bug Reports
* Execution Results

### Included Testing Types

* Positive Testing
* Negative Testing
* Edge Case Testing
* Validation Testing

👉 Spreadsheet test cases:

[QA-Messaging-API-Testing Spreadsheet](https://drive.google.com/drive/folders/117iqkBNMW2QBfW0Ke1XyphnYWVKLWrOi?usp=drive_link&utm_source=chatgpt.com)

---

# 🔌 API Testing (Postman + Newman)

API testing is implemented using:

* Postman Collections
* Environment Variables
* Newman CLI Runner

---

## 🔧 Setup

### Import Collection

```bash
api-testing/postman_collection.json
```

### Import Environment

```bash
api-testing/environment.json
```

---

## ▶️ Run via Newman

```bash
npm install -g newman

newman run postman_collection.json -e environment.json
```

---

# 🤖 Automation Testing

This repository includes automation testing using:

## 🎭 Playwright

Features:

* API & UI automation
* Reusable authentication helper
* Structured test architecture
* CI integration support

### ▶️ Run Playwright

```bash
cd automation/playwright

npm install

npx playwright test
```

---

## 🧪 Selenium

Features:

* Cross-browser automation
* Authentication flow testing
* Basic regression scenarios

---

# 📊 Test Reporting

Test reports include:

* Pass / Fail results
* Execution summaries
* Screenshots
* Automation logs
* Newman execution results

---

# ⚙️ CI/CD (GitHub Actions)

Automation testing is integrated with GitHub Actions.

### Workflow includes:

* Install dependencies
* Execute automation tests
* Generate reports
* CI validation

---

# 🔐 Security & Data Handling

To maintain confidentiality:

* Tokens are hidden
* Sensitive endpoints are anonymized
* Company data is masked
* Environment files do not contain real credentials

---

# 🚀 Future Improvements

Planned future enhancements:

* Performance testing (k6 / Artillery)
* Security validation
* Allure reporting
* Docker integration
* Parallel test execution
* Advanced reporting dashboard

---

# 👤 Author

**Agung Aji**
QA Engineer
