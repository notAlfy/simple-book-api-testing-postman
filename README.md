📚 Simple Book API Testing (Postman)

This project demonstrates end-to-end API testing using Postman for a Simple Book API. It includes request collections, automated test scripts, and validation of core API functionalities such as books, orders, and API client registration.

🚀 Features

* End-to-end API testing for Book Management system
* CRUD operations testing for books and orders
* Automated test scripts using Postman
* Response validation (status codes, response body)
* API client registration testing
* Environment variables usage

🔍 Tested Endpoints

* GET /status → Check API status
<img width="1125" height="801" alt="image" src="https://github.com/user-attachments/assets/891ffaf4-91e2-468c-8762-cd274e630f6c" />

* GET /books → Retrieve list of books
* GET /books/{id} → Retrieve single book details
* POST /orders → Create a new book order
* GET /orders → Retrieve all orders
* GET /orders/{id} → Retrieve a specific order
* PATCH /orders/{id} → Update an existing order
* DELETE /orders/{id} → Delete an order
* POST /api-clients → Register a new API client

## 🧪 Sample Test Scenarios

* Validate API status response (200 OK)
* Verify book list retrieval and data structure
* Validate order creation (201 Created)
* Check order update and deletion functionality
* Negative testing (invalid order ID, missing fields)
* Response time validation

📊 Test Coverage

This project covers:

* Functional testing
* CRUD operation validation
* API workflow testing (Books → Orders → Client Registration)
* Positive and negative test scenarios

🛠️ Tools & Technologies

* Postman
* REST API
* JavaScript (Postman test scripts)

📂 Project Structure

`simple-book-api.postman_collection.json` → Main Postman collection

▶️ How to Run

1. Download the collection JSON file
2. Open Postman
3. Click **Import**
4. Run the collection using Collection Runner

📌 Learning Source

Based on a tutorial by Valentin Despa on YouTube.

💡 Purpose

This project was created to practice API testing and improve skills in Postman, test automation, and API validation.

✨ Feel free to explore and provide feedback!
