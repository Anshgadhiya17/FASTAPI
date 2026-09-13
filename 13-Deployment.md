# 📘 Deployment

## Run with Uvicorn

```bash
uvicorn main:app --host 0.0.0.0 --port 8000
```

---

## Docker (Basic)

```dockerfile
FROM python:3.9
WORKDIR /app
COPY . .
RUN pip install fastapi uvicorn
CMD ["uvicorn", "main:app", "--host", "0.0.0.0"]
```

---

# ✅ End
