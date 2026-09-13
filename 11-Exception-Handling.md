# 📘 Exception Handling

## Example

```python
from fastapi import HTTPException

@app.get("/error")
def error():
    raise HTTPException(status_code=404, detail="Not Found")
```

---

# ✅ End
