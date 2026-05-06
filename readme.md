# 📌 QA Messaging API Testing

This repository showcases a **Quality Assurance (QA) portfolio project** focused on testing a **Messaging API** used in a customer communication system.

The project demonstrates end-to-end QA practices including:

* Manual Testing (Test Plan, Test Cases, Bug Reports)
* API Testing (Postman + Newman)
* Automation Testing (Playwright & Selenium)
* Continuous Integration (GitHub Actions)

> ⚠️ Note: All endpoints, data, and credentials in this project have been anonymized to maintain confidentiality.

---

# 🧠 Project Overview

This project simulates testing of a **Messaging API service**, where users can send and receive messages through a backend system.

### Features Tested:

* Send message
* Message validation
* Authentication
* Error handling
* Negative & edge cases

API testing is a critical part of modern systems because APIs act as the communication layer between services and clients ([arXiv][1]).

---

# 🧪 Testing Scope

## ✅ In Scope

* Functional API testing
* Positive & negative scenarios
* Response validation
* Authentication handling

## ❌ Out of Scope

* Frontend/UI testing
* Performance testing (optional future improvement)
* Security penetration testing

---

# 📂 Project Structure

```
QA-Messaging-API-Testing/
│
├── manual-testing/
│   ├── test-plan.md
│   ├── test-cases.xlsx
│   └── bug-reports/
│
├── api-testing/
│   ├── postman_collection.json
│   ├── environment.json
│   └── README.md
│
├── automation/
│   ├── playwright/
│   └── selenium/
│
├── test-reports/
│
└── README.md
```

---

# 📝 Manual Testing

Manual testing artifacts include:

* **Test Plan** → Defines testing strategy, scope, and objectives
* **Test Cases** → Covers positive, negative, and edge cases
* **Bug Reports** → Documented issues with reproduction steps

👉 Spreadsheet test cases:
[QA-Messaging-API-Testing](https://drive.google.com/drive/folders/117iqkBNMW2QBfW0Ke1XyphnYWVKLWrOi?usp=drive_link)

---

# 🔌 API Testing (Postman + Newman)

This project includes API testing using Postman collections.

### 🔧 Setup

1. Import collection:

```
api-testing/postman_collection.json
```

2. Import environment:

```
api-testing/environment.json
```

### ▶️ Run via Newman

```bash
npm install -g newman
newman run postman_collection.json -e environment.json
```

Postman allows automated API validation using JavaScript-based assertions and environment variables ([GitHub][2]).

---

# 🤖 Automation Testing

Automation is implemented using:

## 🎭 Playwright

* Modern E2E/API automation
* Fast execution
* Built-in reporting

## 🧪 Selenium

* Cross-browser automation
* Industry-standard framework

### ▶️ Run Playwright

```bash
cd automation/playwright
npm install
npx playwright test
```

---

# 📊 Test Reporting

Test reports include:

* Execution results
* Pass / Fail status
* Logs and screenshots (if available)

---

# ⚙️ CI/CD (GitHub Actions)

Automation tests are integrated with CI using GitHub Actions.

### Workflow includes:

* Install dependencies
* Run automation tests
* Generate reports

---

# 🔐 Security & Data Handling

To ensure confidentiality:

* Sensitive data is masked
* Tokens are not exposed
* Endpoints are anonymized

---

# 🚀 Future Improvements

* Performance testing (k6 / Artillery)
* Security testing (basic auth validation)
* Test coverage metrics
* Allure reporting integration

---

# 👤 Author

**Agung Aji**
QA Engineer


