## 📚 Simple Book API Testing (Postman)

This project demonstrates end-to-end API testing using Postman for a Simple Book API. It includes request collections, automated test scripts, and validation of core API functionalities such as books, orders, and API client registration.

Please read the documentation related to the api from the following link: https://github.com/vdespa/introduction-to-postman-course/blob/main/simple-books-api.md

##  Features

* End-to-end API testing for Book Management system
* CRUD operations testing for books and orders
* Automated test scripts using Postman
* Response validation (status codes, response body)
* API client registration testing
* Environment variables usage

##  Tested Endpoints

* GET /status → Check API status
  <img width="1125" height="801" alt="image" src="https://github.com/user-attachments/assets/891ffaf4-91e2-468c-8762-cd274e630f6c" />

* GET /books → Retrieve list of books
  <img width="1126" height="803" alt="image" src="https://github.com/user-attachments/assets/ee11891b-c45f-4b97-a8a4-35799aa4859d" />

* GET /books/{id} → Retrieve single book details
  <img width="1117" height="645" alt="image" src="https://github.com/user-attachments/assets/92179b34-a518-443a-9b70-75eaf61fd0b2" />

* POST /orders → Create a new book order
  <img width="1120" height="490" alt="image" src="https://github.com/user-attachments/assets/45d8372a-15ac-4c19-91ca-e217b15b2e4d" />

* GET /orders → Retrieve all orders
  <img width="1120" height="457" alt="image" src="https://github.com/user-attachments/assets/17852626-a08d-47c5-8e3b-df27a56c46f7" />

* GET /orders/{id} → Retrieve a specific order
  <img width="1115" height="442" alt="image" src="https://github.com/user-attachments/assets/68c783bc-e961-4337-b999-611db7e9f497" />

* PATCH /orders/{id} → Update an existing order
  <img width="1107" height="449" alt="image" src="https://github.com/user-attachments/assets/6f927274-347a-40f3-9b2d-5b74e7e1b9df" />

* DELETE /orders/{id} → Delete an order
  <img width="1119" height="482" alt="image" src="https://github.com/user-attachments/assets/0894ff29-a908-43d7-8a1b-242ca96be79f" />

* POST /api-clients → Register a new API client
  <img width="1111" height="468" alt="image" src="https://github.com/user-attachments/assets/5a3cef50-ea49-4e5d-aeb7-1760ebccd3e1" />


##  Sample Test Scenarios

* Validate API status response (200 OK)
* Verify book list retrieval and data structure
* Validate order creation (201 Created)
* Check order update and deletion functionality
* Negative testing (invalid order ID, missing fields)
* Response time validation

## 📊 Test Coverage

This project covers:

* Functional testing
* CRUD operation validation
* API workflow testing (Books → Orders → Client Registration)
* Positive and negative test scenarios

## 🛠️ Tools & Technologies

* Postman
* REST API
* JavaScript (Postman test scripts)

##  Project Structure

`simple-book-api.postman_collection.json` → Main Postman collection

##  How to Run

1. Download the collection JSON file
2. Open Postman
3. Click **Import**
4. Run the collection using Collection Runner

✨ Feel free to explore and provide feedback!

👨‍💻 Author: Abrar Nawar Alfy  

🔗 GitHub: https://github.com/notAlfy
