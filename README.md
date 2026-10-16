# FastAPI Learning Roadmap 🚀

A beginner-friendly journey to learning **FastAPI**, a modern Python framework for building APIs. This repository contains my notes, practical examples, mini-projects, and exercises as I learn FastAPI step by step.

## 🎯 Goals

- Understand the fundamentals of FastAPI.
- Learn how to build REST APIs using Python.
- Understand HTTP methods, status codes, and request/response handling.
- Work with data validation using Pydantic.
- Connect APIs to databases.
- Implement authentication and authorization.
- Learn API testing, documentation, and deployment.
- Build real-world backend projects.

## 🛠️ Technologies

- **Language:** Python
- **Framework:** FastAPI
- **ASGI Server:** Uvicorn
- **Data Validation:** Pydantic
- **Database:** SQLite / PostgreSQL
- **ORM:** SQLAlchemy
- **Testing:** Pytest
- **Version Control:** Git and GitHub

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/MiniduOshan/fastapi-learning.git
cd fastapi-learning
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Activate it on Linux or macOS:

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install "fastapi[standard]"
```

### 4. Create Your First Application

Create a file named `main.py`:

```python
from fastapi import FastAPI

app = FastAPI(
    title="My First FastAPI",
    description="Learning FastAPI step by step",
    version="1.0.0",
)

@app.get("/")
def home():
    return {"message": "Hello, FastAPI!"}

@app.get("/about")
def about():
    return {
        "framework": "FastAPI",
        "purpose": "Learning backend development",
    }
```

### 5. Run the Application

```bash
fastapi dev main.py
```

Open these URLs in your browser:

- **API:** http://127.0.0.1:8000/
- **Interactive API documentation:** http://127.0.0.1:8000/docs
- **Alternative API documentation:** http://127.0.0.1:8000/redoc

## 🧪 Mini Projects

- [ ] **Hello API** — Create basic endpoints.
- [ ] **Student Management API** — Manage student records.
- [ ] **Task Management API** — Implement CRUD operations.
- [ ] **Authentication API** — Add user registration and login.
- [ ] **Blog API** — Combine database operations and authentication.
- [ ] **AI/ML Prediction API** — Serve a machine learning model through FastAPI.
- [ ] **RAG API** — Expose a document question-answering system through REST endpoints.

## 📖 Learning Resources

- [Official FastAPI Documentation](https://fastapi.tiangolo.com/)
- [Python Official Documentation](https://docs.python.org/3/)
- [Pydantic Documentation](https://docs.pydantic.dev/)
- [SQLAlchemy Documentation](https://docs.sqlalchemy.org/)
- [Pytest Documentation](https://docs.pytest.org/)

## 📈 Progress Tracker

I will use this repository to document what I learn, practice coding, solve problems, and build projects. Each completed topic will include practical examples wherever possible.

## 👨‍💻 Author

**Minidu Oshan**

- GitHub: [@MiniduOshan](https://github.com/MiniduOshan)
- Portfolio: [miniduoshan.me](https://miniduoshan.me)

---

*Learn the fundamentals. Build APIs. Create real-world projects.* 💻

