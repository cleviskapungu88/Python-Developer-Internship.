# Python-Developer-Internship.
This internship focused on Python development, involving two main tasks: building a backend system using Django, MySQL, and REST APIs with full CRUD functionality, and creating an automation script to solve real-world repetitive tasks. It provided practical experience in backend development, database integration, and automation.
# Redynox Python Developer Internship

![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Django](https://img.shields.io/badge/Django-REST%20API-green.svg)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![License](https://img.shields.io/badge/License-Educational-lightgrey.svg)

---

## 📌 Overview

This repository contains work completed under the **Redynox Python Developer Internship Program**. The program focuses on building real-world software development skills using Python, including backend API development and automation scripting.

---

## 🚀 Internship Tasks

### 🧩 Task 1: Full-Stack Python Application (Backend Focus)

#### 🎯 Objective
Develop a functional backend system with database integration and REST APIs.

#### 🛠 Skills Used
- Python (OOP)
- REST API Development
- Database Design
- Debugging & Testing

#### 🧰 Tools
- Django / Flask / FastAPI
- MySQL / SQLite / PostgreSQL
- Postman

#### ⚙️ Features
- CRUD operations
- Input validation
- Error handling
- Clean architecture
- Secure database queries

---

### 🤖 Task 2: Automation Script for Real-World Problem

#### 🎯 Objective
Build a Python automation tool to solve repetitive real-world tasks.

#### 🛠 Skills Used
- Python Scripting
- File Processing
- System Automation
- Scheduling

#### 🧰 Tools
- Python OS libraries
- Pandas (optional)
- Cron / Task Scheduler

#### ⚙️ Features
- Input/config file handling
- Logging execution results
- Error handling
- CLI support
- Optional scheduling

---

## 📁 Project Structure
Redynox-Python-Internship/
│
├── task1_backend_api/
│ ├── manage.py
│ ├── requirements.txt
│ ├── db.sqlite3 / MySQL DB
│ ├── inventory/
│ │ ├── models.py
│ │ ├── views.py
│ │ ├── serializers.py
│ │ ├── urls.py
│ │ └── tests.py
│ └── config/
│ ├── settings.py
│ └── urls.py
│
├── task2_automation_script/
│ ├── main.py
│ ├── config.json
│ ├── utils.py
│ └── logs/
│
├── postman_collection.json
├── requirements.txt
└── README.md

---

## ⚡ Setup Instructions

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/redynox-python-internship.git
cd redynox-python-internship
### 2️⃣ Create Virtual Environment
```bash
python -m venv venv
Activate environment:

Windows:
```bash
venv\Scripts\activate

Mac/Linux:
```bash
source venv/bin/activate

3️⃣ Install Dependencies
```bash
pip install -r requirements.txt

4️⃣ Configure Database (Task 1)

For MySQL:
```MySQL

CREATE DATABASE internship_db;

Update .env or settings.py with:

DB_ENGINE=mysql
DB_NAME=internship_db
DB_USER=root
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=3306
5️⃣ Run Migrations
```bash
python manage.py migrate
6️⃣ Start Server
```bash
python manage.py runserver

API will be available at:

http://127.0.0.1:8000/api/
7️⃣ Run Automation Script (Task 2)
```bash
python task2_automation_script/main.py

🧪 Testing
Use Postman to test REST API endpoints
Import:
postman_collection.json

Run test cases:

CRUD operations
Stock updates
Error handling
Authentication (if included)
