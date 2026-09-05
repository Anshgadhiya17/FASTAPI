# 📘 Basic FastAPI App

## Example

```python
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def home():
    return {"message": "Hello World"}
```

---

## Run

```bash
uvicorn main:app --reload
```

---

## Swagger Docs

```
http://127.0.0.1:8000/docs
```

---

# ✅ End
