# python-flaskcrud-student-registration-project
Student Management System

A simple Flask CRUD app for managing students using MySQL (XAMPP).
It demonstrates basic Create, Read, Update, and Delete operations.

✨ Features

View students in a table

Add new students

Edit student details

Delete students

Search functionality

Responsive layout

Font Awesome icons

🛠️ Tech Stack

Backend: Flask (Python)

Database: MySQL (XAMPP)

Frontend: HTML, CSS, JavaScript

Icons: Font Awesome

📁 Project Structure
student-management-system/
│
├── app.py
│
└── templates/
    ├── index.html
    ├── add.html
    └── edit.html

📌 Requirements

Python 3.7+

XAMPP

MySQL running

pip

⚙️ Setup
Install Dependencies
pip install flask mysql-connector-python

Create Database

Open phpMyAdmin:

http://localhost/phpmyadmin


Run:

CREATE DATABASE IF NOT EXISTS flaskcrud;

USE flaskcrud;

CREATE TABLE IF NOT EXISTS students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL UNIQUE
);

▶️ Run the App

Start MySQL in XAMPP

Run:

python app.py


Open:

http://localhost:5000

🔧 Configuration
Change Port
app.run(debug=True, port=5000)

Update Database Settings

Edit get_db() in app.py.

🐛 Troubleshooting

Database error:

Ensure MySQL is running

Confirm database exists

Check credentials

Module error:

pip install flask mysql-connector-python

👨‍💻 Author

Felix Mumo
AI Class – 2026
