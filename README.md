# Django Intro Project

This project covers the basics of Django, including:

- Creating a virtual environment
- Installing Django
- Creating a Django project
- Creating an app
- Routing and URLs
- Including app URLs
- Django settings overview
- Templates
- Static files

---

## 🚀 Setup Instructions

### 1️⃣ Create Virtual Environment

Create a virtual environment named `.venv`:

```bash
python -m venv .venv
```

### 2️⃣ Activate Virtual Environment

**On Windows:**

```bash
.venv\Scripts\activate
```

**On macOS / Linux:**

```bash
source .venv/bin/activate
```

---

### 3️⃣ Install Django

```bash
pip install django
```

(Optional) Save dependencies:

```bash
pip freeze > requirements.txt
```

---

### 4️⃣ Create Django Project

```bash
django-admin startproject config .
```

---

### 5️⃣ Run Development Server

```bash
python manage.py runserver
```

Open your browser and go to:

```
http://127.0.0.1:8000/
```

---

### 6️⃣ Create a Django App

```bash
python manage.py startapp core
```

Add the app to `INSTALLED_APPS` in `settings.py`.

---

## 📚 Topics Covered

- Virtual Environment (`.venv`)
- Django Installation
- Project Structure
- Creating Apps
- URL Routing
- Including App URLs
- Templates Setup
- Static Files Configuration

---

## 📁 Project Structure (Basic)

```
project structure/
│
├── .venv/
├── myProject/
        ├── myProject/
        ├── myapp/        
        ├── manage.py
└── README.md
```

---

## 🧠 Requirements

- Python 3.8+
- pip

---

## 📌 Notes

Always activate the virtual environment before running the project.

---

Happy Coding! 🚀
