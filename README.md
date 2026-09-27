# API Testing – Postman

## 📌 Project Overview

This project demonstrates API testing using Postman. The project covers functional, positive, negative, and response validation scenarios for a public REST API.

## 🛠️ Tools Used

* Postman
* REST API
* JSON
* JavaScript
* GitHub

## 🧪 API Testing Coverage

The following HTTP methods are covered:

* GET
* POST
* PUT
* PATCH
* DELETE

## 📋 Test Scenarios

| Test Scenario           | Method | Expected Result |
| ----------------------- | ------ | --------------- |
| Retrieve list of users  | GET    | 200 OK          |
| Retrieve a single user  | GET    | 200 OK          |
| Retrieve invalid user   | GET    | 404 Not Found   |
| Create a user           | POST   | 201 Created     |
| Update a user           | PUT    | 200 OK          |
| Partially update a user | PATCH  | 200 OK          |
| Delete a user           | DELETE | 204 No Content  |

## 🔍 Validations

Postman assertions are used to validate:

* HTTP status codes
* JSON response format
* Required response fields
* User ID
* Response data
* Update timestamp
* Empty response body for DELETE
* API response behavior for negative scenarios

## 📁 Project Files

### API_Test_Cases.xlsx

Contains detailed API test scenarios, test data, expected results, priority and execution status.

### API-Testing-ReqRes.postman_collection.json

Contains the Postman collection with API requests and automated post-response assertions.

## 🎯 Objective

The objective of this project is to demonstrate practical API testing skills including request creation, response validation, negative testing, CRUD operations and automated assertions using Postman.

## 👩‍💻 Tester

**Samidha Shinde**

QA Tester | Manual Testing | API Testing | Postman | Jira

