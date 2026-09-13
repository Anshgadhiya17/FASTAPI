# 📘 File Upload

## Example

```python
from fastapi import UploadFile, File

@app.post("/upload")
def upload(file: UploadFile = File(...)):
    return {"filename": file.filename}
```

---

# ✅ End
