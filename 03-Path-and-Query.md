# 📘 Path & Query Parameters

## Path Parameter

```python
@app.get("/users/{id}")
def get_user(id: int):
    return {"id": id}
```

---

## Query Parameter

```python
@app.get("/users")
def get_users(limit: int = 10):
    return {"limit": limit}
```

---

# ✅ End
