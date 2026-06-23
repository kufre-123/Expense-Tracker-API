# Expense Tracker API

A simple backend API built using FastAPI to manage personal expenses. The project focuses on learning backend development concepts such as API design, database integration, and CRUD operations.

---

## Features

* Create new expenses
* Retrieve all expenses
* Update existing expenses
* Delete expenses
* Structured data storage using SQLite

---

## Tech Stack

* Python
* FastAPI
* SQLAlchemy
* SQLite
* Uvicorn

---

## Project Structure

```
Expense-Tracker-API/
├── main.py
├── models.py
├── database.py
├── schemas.py
```

---

## How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/yourusername/expense-tracker-api.git
cd expense-tracker-api
```

### 2. Install dependencies

```
pip install fastapi uvicorn sqlalchemy
```

### 3. Run the server

```
uvicorn main:app --reload
```

### 4. Open API documentation

```
http://127.0.0.1:8000/docs
```

---

## API Endpoints

* POST `/expenses/` → Create an expense
* GET `/expenses/` → Retrieve all expenses
* PUT `/expenses/{id}` → Update an expense
* DELETE `/expenses/{id}` → Delete an expense

---

## What I Learned

* Building REST APIs using FastAPI
* Structuring backend applications
* Working with databases using SQLAlchemy
* Implementing CRUD operations
* Understanding backend architecture basics

---

## Author

Kufre Wilson
GitHub: https://github.com/kufre-123
LinkedIn: https://www.linkedin.com/in/kufre-wilson
