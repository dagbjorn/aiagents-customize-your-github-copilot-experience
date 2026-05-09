# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful APIs using the FastAPI framework in Python. This assignment will help you understand API endpoints, request/response handling, and basic CRUD operations.

## 📝 Tasks

### 🛠️ Task 1: Set Up FastAPI Project

#### Description
Initialize a new FastAPI project and create a basic application structure.

#### Requirements
Completed program should:
- Install FastAPI and Uvicorn
- Create a main.py file with a basic FastAPI app
- Add a root endpoint (GET /) that returns a welcome message

### 🛠️ Task 2: Implement CRUD Endpoints

#### Description
Add endpoints to perform Create, Read, Update, and Delete operations on a simple resource (e.g., items or users).

#### Requirements
Completed program should:
- Define a Pydantic model for your resource
- Implement endpoints for:
  - Creating a new resource (POST)
  - Reading all resources (GET)
  - Reading a single resource by ID (GET)
  - Updating a resource by ID (PUT)
  - Deleting a resource by ID (DELETE)

### 🛠️ Task 3: Test Your API

#### Description
Test your API using a tool like curl, HTTPie, or the built-in FastAPI docs (Swagger UI).

#### Requirements
Completed program should:
- Successfully handle requests and responses for all endpoints
- Return appropriate status codes and error messages
- Document endpoints using FastAPI's automatic docs

---

Keep your code organized and add comments to explain your logic. Explore FastAPI's documentation for more features. Good luck and have fun building your API!