# 📘 Authentication (JWT)

## Install

```bash
pip install python-jose passlib
```

---

## Example

```python
from jose import jwt

SECRET_KEY = "secret"

token = jwt.encode({"user": "abc"}, SECRET_KEY, algorithm="HS256")
```

---

# ✅ End
