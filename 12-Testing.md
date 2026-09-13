# 📘 Testing FastAPI

## Install

```bash
pip install pytest
```

---

## Example

```python
from fastapi.testclient import TestClient

client = TestClient(app)

def test_home():
    response = client.get("/")
    assert response.status_code == 200
```

---

# ✅ End
