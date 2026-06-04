# Trello API Testing with Postman

## Project Overview

REST API testing of Trello board management functionality using Postman.

### Covered Scenarios

* Create Board
* Create Lists
* Create Cards
* Status Code Validation
* Response Time Validation
* Response Body Validation
## API 01. Create Board

**Method:** POST

**Endpoint:** `/1/boards`

### Validation

* Board created successfully
* Response body returned

![Create Board](./Create-Board.png)

---

## API 02. Create Left List

**Method:** POST

**Endpoint:** `/1/lists`

### Validation

* Status Code = 200
* Response Time < 1000 ms
* Name is String

![Create Left List](./Create-Left-List.png)

---

## API 03. Create Right List

**Method:** POST

**Endpoint:** `/1/lists`

### Validation

* Status Code = 200
* Response Time < 1000 ms
* Name is String

![Create Right List](./Create-Right-List.png)

---

## API 04. Create Card in Left List

**Method:** POST

**Endpoint:** `/1/cards`

### Validation

* Status Code = 200
* Response Time < 200 ms
* ID is String

![Create Left Card](./Create-Left-Card.png)

---

## API 05. Create Card in Right List

**Method:** POST

**Endpoint:** `/1/cards`

### Validation

* Status Code = 200
* Response Time < 1000 ms
* ID is String

![Create Right Card](./Create-Right-Card.png)

---

## Tools Used

## Postman Collection Structure

The collection contains requests for complete Trello board management workflow.

![Collection Structure](./Postman-Collection.png.png)
* Postman
* REST API
* JSON
* JavaScript Assertions
* Trello API
