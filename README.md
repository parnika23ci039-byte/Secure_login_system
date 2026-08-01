# Secure_login_system
# 🔐 Secure Login System

## 📌 Project Overview

The **Secure Login System** is a web-based authentication application developed using **Flask**, **SQLite**, and **bcrypt**. It provides a secure environment where users can register, log in, and access protected pages using encrypted passwords and session-based authentication.

The project demonstrates secure authentication practices, including password hashing, user validation, session management, and database integration. It is designed as a beginner-friendly cybersecurity and web development project.

---

## 🎯 Project Objectives

- Develop a secure user authentication system.
- Implement user registration and login functionality.
- Store user credentials securely using password hashing.
- Manage authenticated sessions.
- Protect restricted pages from unauthorized access.
- Demonstrate secure web development practices.

---

## ✨ Features

- 🔐 User Registration
- 👤 User Login
- 🔑 Password Hashing using bcrypt
- 🗄️ SQLite Database Integration
- 🔒 Secure Authentication
- 🚪 Logout Functionality
- 🛡️ Protected Dashboard
- 📱 Simple and Responsive Interface

---

## 🛠️ Technologies Used

- Python
- Flask
- SQLite
- Flask-Bcrypt
- Flask-Login
- HTML
- CSS
- Google Colab

---

## 📂 Project Structure

```
Secure-Login-System/
│
├── app.py
├── users.db
├── requirements.txt
├── README.md
│
├── templates/
│   ├── index.html
│   ├── register.html
│   ├── login.html
│   └── dashboard.html
│
├── static/
│   └── style.css
│
└── screenshots/
    ├── home_page.png
    ├── register_page.png
    ├── login_page.png
    ├── dashboard.png
```

---

## ⚙️ Workflow

1. User opens the application.
2. New users register with a username and password.
3. Passwords are securely hashed using bcrypt.
4. User information is stored in the SQLite database.
5. Registered users log in with valid credentials.
6. Flask-Login authenticates the session.
7. Authenticated users access the protected dashboard.
8. Users can securely log out.

---

## 🔒 Security Features

- Password Hashing with bcrypt
- Secure User Authentication
- Session Management
- Protected Routes
- Secure Login Validation
- SQLite Database Storage

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/Secure-Login-System.git
```

### Install Required Libraries

```bash
pip install flask flask-bcrypt flask-login
```

### Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 📸 Project Screenshots

- Home Page
- User Registration
- Login Page
- User Dashboard
- Successful Login

---

## 🎓 Learning Outcomes

Through this project, I learned:

- Flask Web Development
- User Authentication
- Password Encryption using bcrypt
- SQLite Database Integration
- Session Management
- Secure Login Implementation
- Backend Development
- Web Security Fundamentals

