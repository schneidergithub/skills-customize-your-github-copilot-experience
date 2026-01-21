# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small RESTful API using the FastAPI framework to practice designing endpoints, validating request/response data with Pydantic models, and running a lightweight development server.

## 📝 Tasks

### 🛠️ Task 1 — Core API Endpoints

#### Description
Create a FastAPI app that exposes CRUD endpoints for a simple resource (e.g., `Item`). Implement in-memory storage for the resource so the app runs without a database.

#### Requirements
- Implement endpoints: `GET /items`, `GET /items/{id}`, `POST /items`, `PUT /items/{id}`, `DELETE /items/{id}`.
- Use Pydantic models for request validation and response models.
- Return appropriate HTTP status codes and error messages on invalid requests.

### 🛠️ Task 2 — Extras & Testing

#### Description
Add one or more polish features and provide simple tests or examples demonstrating the API.

#### Requirements
- Add input validation (e.g., required fields, length limits).
- Provide example `curl` or HTTPie commands in this README to exercise each endpoint.
- (Optional) Add a small `tests/` folder with a few `pytest` tests for the core logic.

## 🔧 Prerequisites
- Python 3.9+ installed.
- `pip` available to install dependencies.

## ⚙️ Setup & Run
Create and activate a virtual environment, install dependencies, and run the app with `uvicorn`:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
uvicorn starter-code:app --reload
```

The API will be available at `http://127.0.0.1:8000` and automatic docs at `http://127.0.0.1:8000/docs`.

## 📁 Starter Code
See `starter-code.py` — a minimal FastAPI app with `Item` models and in-memory storage to get you started.

## 📦 Submission
- Submit the updated `starter-code.py` implementation (or a new file) and this `README.md` with any notes.
- If you add tests, include instructions to run them.

## 🧾 Grading Rubric
- Functionality (50%): Endpoints implemented and behaving correctly.
- Code Quality (20%): Clear structure, modular functions, and Pydantic models.
- Documentation & Examples (20%): README includes run steps and example requests.
- Extras & Tests (10%): Optional features and basic tests.

## 🚀 Optional Extensions
- Add persistent storage with SQLite using `sqlmodel` or `sqlite3`.
- Add authentication (API keys or OAuth) for protected endpoints.
- Deploy the app to a free hosting provider (e.g., Render, Fly, or Railway).

## 🔗 Resources
- FastAPI docs: https://fastapi.tiangolo.com/
- Pydantic docs: https://docs.pydantic.dev/
- Uvicorn docs: https://www.uvicorn.org/

Good luck — build something you’re proud of!
