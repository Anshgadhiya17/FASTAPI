# 📘 FastAPI Core Concepts (Interview Ready)

---

## 🔹 What is FastAPI?

FastAPI is a modern Python web framework used to build high-performance APIs using asynchronous programming and type hints.

It is based on:
- Starlette (for web handling)
- Pydantic (for data validation)

---

## 🔹 Why FastAPI is Fast?

- Uses **ASGI** (Asynchronous Server Gateway Interface)
- Supports async/await
- Non-blocking I/O operations

➡ That’s why it is faster than Flask and Django (in API use cases)

---

## 🔹 FastAPI vs Flask

| FastAPI | Flask |
|--------|-------|
| Async support | Mostly sync |
| Built-in validation | Manual validation |
| Auto docs | No auto docs |
| High performance | Moderate |

---

## 🔹 What is ASGI?

ASGI is a specification for handling asynchronous requests.

➡ It allows FastAPI to:
- Handle multiple requests at the same time
- Work efficiently with APIs

---

## 🔹 What is Pydantic?

Pydantic is used for:
- Data validation
- Data parsing

Example:
```python
class User(BaseModel):
    name: str
    age: int
```

➡ Ensures correct data types automatically.

---

## 🔹 What is Dependency Injection?

Dependency Injection allows reuse of logic like:
- Database connection
- Authentication

Example:
```python
def get_db():
    return db
```

➡ Improves code reusability and structure.

---

## 🔹 What is Middleware?

Middleware runs before and after request.

Used for:
- Logging
- Authentication
- CORS

---

## 🔹 What is CORS?

CORS (Cross-Origin Resource Sharing) allows frontend and backend to communicate.

➡ Required when frontend & backend are on different ports.

---

## 🔹 What is CRUD in FastAPI?

CRUD means:
- Create → POST
- Read → GET
- Update → PUT
- Delete → DELETE

---

## 🔹 What is ORM?

ORM (Object Relational Mapping) is used to interact with database using Python code.

Example:
- SQLAlchemy

---

## 🔹 What is JWT Authentication?

JWT (JSON Web Token) is used for secure authentication.

Flow:
1. User logs in
2. Server gives token
3. Client sends token in requests

---

## 🔹 What is Background Task?

Used to run tasks after response.

Example:
- Send email
- Logging

---

## 🔹 What is Uvicorn?

Uvicorn is an ASGI server used to run FastAPI apps.

```bash
uvicorn main:app --reload
```

---

## 🔹 When to Use FastAPI?

- Building REST APIs
- Microservices
- AI/ML model APIs
- High-performance backend

---

# 🎯 Interview Summary (Short Answer)

FastAPI is a high-performance Python web framework used for building APIs.  
It uses async programming, Pydantic for validation, and ASGI for speed.  
It provides automatic documentation and is widely used for modern backend and AI-based applications.

---

# ✅ End
