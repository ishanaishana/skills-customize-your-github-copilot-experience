# 📘 Assignment: FastAPI REST API

## 🎯 Objective

Learn how to build and test RESTful APIs using the FastAPI framework in Python. You will create endpoints, handle requests, and return JSON responses.

## 📝 Tasks

### 🛠️ Task 1: Set Up FastAPI Project

#### Description
Install FastAPI and Uvicorn, and create a basic FastAPI application with a root endpoint.

#### Requirements
Completed program should:
- Install FastAPI and Uvicorn
- Create a main Python file (e.g., main.py)
- Define a root endpoint (`/`) that returns a welcome message as JSON

### 🛠️ Task 2: Create CRUD Endpoints

#### Description
Implement RESTful endpoints for managing a list of items (e.g., books, tasks, or products) with create, read, update, and delete operations.

#### Requirements
Completed program should:
- Define a data model using Pydantic
- Implement endpoints for:
  - Creating a new item (POST)
  - Reading all items (GET)
  - Updating an item by ID (PUT)
  - Deleting an item by ID (DELETE)
- Return appropriate JSON responses and status codes

#### Example Output
```json
{
  "id": 1,
  "name": "Sample Item",
  "description": "This is a sample item."
}
```
