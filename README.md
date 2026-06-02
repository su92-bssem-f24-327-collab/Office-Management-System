#  Office Management System

A complete **Office Management System** built with **Flask** (Python) and **SQLite/MySQL** database. Supports two user roles — **Admin** and **Employee** — with role-based access control.

---

##  Login Credentials

 Admin       
  `admin`   
  `admin123 

Employee    
 `employee1
 `emp123`  

---

##  Features

###  Admin Panel
- Add / Edit / Delete employees
- View all employee details
- Manage attendance records
- Generate reports
- View system dashboard

###  Employee Panel
- View personal profile
- Mark daily attendance
- View attendance history
- Apply for leave
- View work updates

---

## 🛠️ Tech Stack

| Technology     | Purpose        |
|------------    |---------       |
| Python 3.x     | Backend logic  |
| Flask          | Web framework  |
| SQLite / MySQL | Database       |
| HTML5, CSS3    | Frontend UI    |
| Jinja2         | Templating     |
| Flask-Login    | Authentication |

---

## 📦 Installation Guide

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Step 1: Clone the Repository

git clone https://github.com/yourusername/office-management-system.git
cd office-management-system

### Step 2: Create Virtual Environment

Windows
python -m venv venv
venv\Scripts\activate

Mac / Linux
python -m venv venv
source venv/bin/activate

### Step 3: Install Dependencies
pip install flask
pip install flask-sqlalchemy
pip install flask-login

### Step 4: Initialize Database
python
>> from app import db
>> db.create_all()
>> exit()

### Step 5: Run the Application
python run.py

### Step 6: Open in Browser
text
http://127.0.0.1:5000
 Test Credentials
Type	     Username    	Password
Admin	     admin	      admin123
Employee	  employee1	  emp123


