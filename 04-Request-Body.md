# 📘 Request Body (Pydantic)

## Example

```python
from pydantic import BaseModel

class User(BaseModel):
    name: str
    age: int

@app.post("/users")
def create_user(user: User):
    return user
```

---

# ✅ End
