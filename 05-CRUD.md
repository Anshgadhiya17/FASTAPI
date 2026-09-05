# 📘 CRUD Operations

## Create

```python
@app.post("/users")
def create_user(user: User):
    return user
```

---

## Read

```python
@app.get("/users")
def get_users():
    return []
```

---

## Update

```python
@app.put("/users/{id}")
def update_user(id: int, user: User):
    return {"id": id, "user": user}
```

---

## Delete

```python
@app.delete("/users/{id}")
def delete_user(id: int):
    return {"message": "Deleted"}
```

---

# ✅ End
