# 🐾 Pet Store API End-to-End Testing

## 📌 Project Overview

This project demonstrates end-to-end API testing using Postman and Newman for the Swagger Petstore API.

It includes CRUD operations, dynamic data handling, and file upload validation.

---

## 🛠️ Technologies Used

* Postman
* Newman (CLI)
* JavaScript (Postman test scripts)
* HTML Extra Reporter

---

## 🔄 Test Flow

1. Add a new pet to store
2. Find pets by status
3. Update an existing pet
4. Find pet by ID
5. Update pet using form data
6. Upload pet image
7. Delete pet

---

## ✅ Validations Performed

* Status code validation
* Response time validation
* JSON structure validation
* Key-value assertions
* Array and object validations
* Dynamic Pet ID handling using environment variables
* File upload verification (file name, size, message)

---

## ▶️ How to Run Tests

### Run using Newman:

```bash
newman run "Pet store E2E test.postman_collection.json" -e "New Environment.postman_environment.json" -r cli,htmlextra
```

### Generate HTML Report:

```bash
newman run "Pet store E2E test.postman_collection.json" -e "New Environment.postman_environment.json" -r htmlextra --reporter-htmlextra-export "PetStoreReport.html"
```

---

## 📊 Test Report

HTML Extra report is generated showing:

* Total assertions
* Passed/Failed tests
* Execution time
* Detailed request/response logs

---

## 💡 Key Learning

* Dynamic data handling using environment variables
* End-to-end API test flow design
* Assertion strategies in Postman
* Running API tests via command line using Newman
* Generating professional test reports

---

Erandi Punchihewa
QA Automation Enthusiast | Selenium | Postman | API Testing

