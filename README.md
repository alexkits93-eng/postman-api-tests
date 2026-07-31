# ReqRes API Testing

This project demonstrates manual API testing using Postman.

The collection includes CRUD operations, authentication scenarios, negative test cases and automated validation scripts written in JavaScript.

---

## Technologies

- Postman
- REST API
- JavaScript
- JSON
- HTTP
- Environment Variables

---

## Tested Endpoints

### Authentication

- POST Login Success
- POST Login Missing Password

### Users

- GET Users List
- POST Create User
- PUT Update User
- PATCH Partial Update User
- DELETE User

### Negative Tests

- GET User Not Found
- POST Create User with Empty Body

---

## Test Coverage

✔ Status code validation

✔ Response body validation

✔ Response time validation

✔ JSON structure validation

✔ Required fields validation

✔ Data type validation

✔ Environment variables

✔ CRUD testing

✔ Authentication testing

✔ Negative testing

---

## Environment Variables

- baseUrl
- apiKey
- createdUserId
- token
- userName
- userJob
- updatedJob

---

## Project Structure

```
ReqRes API Tests
│
├── Authentication
│   ├── POST - Login Success
│   └── POST - Login Missing Password
│
├── Users
│   ├── GET - Get Users List
│   ├── POST - Create User
│   ├── PUT - Update User
│   ├── PATCH - Partial Update User
│   └── DELETE - Delete User
│
└── Negative Tests
    ├── GET - User Not Found
    └── POST - Create User Empty Body
```

---

## How to Run

1. Import the collection into Postman.
2. Import the environment.
3. Set your ReqRes API Key.
4. Run the collection using Collection Runner.

---

## Author

Alex Kits
