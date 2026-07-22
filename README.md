# FastAPI Patient Management API

A simple REST API built with **FastAPI** for managing patient records. This project demonstrates the fundamentals of building APIs using Python and FastAPI, including creating endpoints, handling HTTP requests, and working with JSON data.

---

## 🚀 Features

- Create a new patient
- View all patients
- Retrieve a patient by ID
- Update patient information
- Delete a patient
- JSON-based data storage
- Interactive API documentation using Swagger UI

---

## 🛠️ Technologies Used

- Python 3.14
- FastAPI
- Uvicorn
- uv (Package Manager)

---

## 📁 Project Structure

```
fastapi/
│── main.py
│── patients.json
│── pyproject.toml
│── uv.lock
│── README.md
└── .gitignore
```

---

## 📦 Installation

### Clone the repository

```bash
git clone https://github.com/mayanknegi2913/fastapi.git
```

### Move into the project directory

```bash
cd fastapi
```

### Create a virtual environment

```bash
python -m venv .venv
```

### Activate the virtual environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux/macOS

```bash
source .venv/bin/activate
```

### Install dependencies

Using **uv**

```bash
uv sync
```

---

## ▶️ Run the Application

```bash
uv run uvicorn main:app --reload
```

The application will start on:

```
http://127.0.0.1:8000
```

---

## 📖 API Documentation

FastAPI automatically generates interactive documentation.

Swagger UI

```
http://127.0.0.1:8000/docs
```

ReDoc

```
http://127.0.0.1:8000/redoc
```

---

## 📌 Future Improvements

- Database Integration (SQLite/PostgreSQL)
- User Authentication
- Data Validation
- Docker Support
- Unit Testing
- Deployment on Cloud

---

## 👨‍💻 Author

**Mayank Negi**

GitHub: https://github.com/mayanknegi2913

Email: mayanknegi1306@gmail.com