# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a simple RESTful API using the FastAPI framework. Students will define endpoints, use Pydantic models for request/response schemas, and run the API server locally.

## 🧭 Difficulty & Time

- **Difficulty:** Intermediate
- **Estimated time:** 1–2 hours

## 🔁 Prerequisites

- Python basics (functions, data types)
- Familiarity with HTTP methods (GET, POST) is helpful
- `pip` and virtual environments

## 📁 Starter files

- `main.py` — skeleton FastAPI application

## 📝 Tasks

### 🛠️ Task 1 — Simple API Endpoints

#### Description
Implement a FastAPI app that serves basic endpoints for managing a collection of items (e.g., books, tasks).

#### Requirements
Completed program should:

- Use FastAPI to create an application instance.
- Define at least two endpoints: a `GET /items` that returns a list and a `POST /items` that accepts a new item.
- Use a Pydantic model to validate request bodies.
- Keep items in an in-memory list (no database required).
- Return appropriate status codes (200 for GET, 201 for POST).

### 🛠️ Task 2 — Path Parameters and Validation

#### Description
Extend the API with path parameters and input validation.

#### Requirements

- Add a `GET /items/{item_id}` endpoint returning a single item by ID.
- Validate that `item_id` is an integer and return 404 if not found.
- Include error handling using FastAPI's HTTPException.

## 💡 Hints

- Install FastAPI and Uvicorn: `pip install fastapi uvicorn`.
- Run the server with `uvicorn main:app --reload`.
- Use `from pydantic import BaseModel` for schemas.

## ▶️ How to run

1. Create a virtual environment and install dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install fastapi uvicorn
   ```
2. Start the application:
   ```bash
   uvicorn main:app --reload
   ```
3. Open `http://127.0.0.1:8000/docs` to explore the automatically generated API docs.

## ✅ Learning Outcomes

- Understand REST principles and HTTP methods.
- Build a simple API using FastAPI.
- Use Pydantic for data validation.
- Work with path parameters and error handling.

## 📤 Submission

Submit the `main.py` file with your implementation and any notes about additional features you added.
