# Office Management System

A complete **Office Management System** built with **Flask (Python)** and **SQLite/MySQL** database. It supports two user roles — **Admin** and **Employee** — with role-based access control.

---

## Login Credentials

### Admin

* **Username:** `admin`
* **Password:** `admin123`

### Employee

* **Username:** `employee1`
* **Password:** `emp123`

---

## Features

### Admin Panel

* Add, Edit, and Delete Employees
* View All Employee Details
* Manage Attendance Records
* Generate Reports
* View System Dashboard

### Employee Panel

* View Personal Profile
* Mark Daily Attendance
* View Attendance History
* Apply for Leave
* View Work Updates

---

## Tech Stack

| Technology     | Purpose           |
| -------------- | ----------------- |
| Python 3.x     | Backend Logic     |
| Flask          | Web Framework     |
| SQLite / MySQL | Database          |
| HTML5, CSS3    | Frontend UI       |
| Jinja2         | Templating Engine |
| Flask-Login    | Authentication    |

---

## Installation Guide

### Prerequisites

* Python 3.8 or Higher
* pip Package Manager

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/office-management-system.git
cd office-management-system
```

### Step 2: Create a Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Mac / Linux

```bash
python -m venv venv
source venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install flask
pip install flask-sqlalchemy
pip install flask-login
```

### Step 4: Initialize the Database

```bash
python
```

```python
from app import db
db.create_all()
exit()
```

### Step 5: Run the Application

```bash
python run.py
```

### Step 6: Open in Browser

```text
http://127.0.0.1:5000
```

---

## Test Credentials

| Role     | Username  | Password |
| -------- | --------- | -------- |
| Admin    | admin     | admin123 |
| Employee | employee1 | emp123   |

---

## Project Structure

```text
office-management-system/
│
├── app.py
├── run.py
├── models.py
├── templates/
├── static/
├── database.db
├── requirements.txt
└── README.md
```

---

## License

This project is for educational and learning purposes.
