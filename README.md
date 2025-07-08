# 🧪 FakeStore API Testing – Postman + Newman

## 📋 Project Overview

This repository contains API tests for the **FakeStore API**, created using Postman. It includes a Postman **collection**, **environment file**, and automated test scripts executed via **Newman CLI**. Results are exported as a clean **HTML report**, viewable locally or hosted via GitHub Pages.

## 🚀 Tools & Technologies

- **Postman**: API development and request building
- **Newman**: CLI runner for Postman collections
- **HTML Report**: Visual summary of test execution

## 📁 Project Structure

```
├── postman_collection.json 
├── postman_environment.json
├── Newman Test Report/ 
│ ├── newman-report.html 
└── README.md
```

## ✅ Features Covered
- RESTful API testing (GET, POST, PUT, DELETE)
- Status code and header validation
- Response body schema verification
- Response time assertion
- Environment variable support
- HTML report generation with Newman

## 🚀 How to Run the Tests
✅ Prerequisites
- [Node.js](https://nodejs.org/) installed
- Newman installed globally
Install Newman:
```bash
npm install -g newman
```
▶️ Run Collection from Terminal
```bash
newman run postman_collection.json -e postman_environment.json
```
💾 Run and Export HTML Report
```bash
newman run postman_collection.json \
  -e postman_environment.json \
  -r cli,html \
  --reporter-html-export "Newman Test Report/newman-report.html"
```
## 📸 Test Report Screenshot
![newman report](https://github.com/user-attachments/assets/dd51ea69-e2e6-4b0b-9ab8-8813bd949ca7)

## 🌐 Live Newman HTML Report
 👉 [Click to View the Full Test Report](https://Akram-BSMRSTU.github.io/FakeStore_APiTesting/Newman%20Test%20Report/newman-report.html)

## 👨‍💻 Author  
**Akram Khan** – SQA Engineer  
📧 [akramkhanarafat12@gmail.com](mailto:akramkhanarafat12@gmail.com)
