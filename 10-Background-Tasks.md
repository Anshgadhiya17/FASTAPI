# 📘 Background Tasks

## Example

```python
from fastapi import BackgroundTasks

def task():
    print("Running task")

@app.get("/")
def run_task(background_tasks: BackgroundTasks):
    background_tasks.add_task(task)
    return {"message": "Task started"}
```

---

# ✅ End
