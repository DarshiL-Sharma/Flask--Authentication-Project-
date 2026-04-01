# Flask--Authentication-Project-
Flask-based authentication system with user registration, login, and protected routes. Uses Flask-Login, SQLAlchemy, and secure password hashing. Built by Darshil Sharma to demonstrate session management and backend authentication fundamentals.
# 🔐 Flask Authentication System

A simple and secure user authentication system built with **Flask**, featuring user registration, login, logout, and protected routes. This project demonstrates best practices for handling user credentials, session management, and database integration using SQLite.

---

## 🚀 Features

* User registration with hashed passwords
* Secure login authentication
* Session management using Flask-Login
* Protected routes (only accessible when logged in)
* Flash messages for user feedback
* SQLite database integration with SQLAlchemy
* File download route support

---

## 🛠️ Tech Stack

* Python
* Flask
* Flask-Login
* Flask-SQLAlchemy
* SQLite
* Werkzeug Security

---

## 📂 Functionality Overview

* **Register:** Create a new account with email, name, and password
* **Login:** Authenticate users using hashed password verification
* **Logout:** End user session securely
* **Secrets Page:** Restricted content accessible only after login
* **Download Route:** Allows users to download files from the server

---

## 🔒 Security Highlights

* Passwords are hashed using Werkzeug’s `generate_password_hash`
* Authentication handled via Flask-Login
* Route protection with `@login_required`
* User session tracking and management

---

## 📌 Purpose

This project is ideal for beginners learning:

* Flask authentication flow
* Database integration
* Secure password handling
* User session management

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash
pip install flask flask-login flask-sqlalchemy
```

3. Run the app:

```bash
python app.py
```

4. Open in browser:

```
http://127.0.0.1:5000/
```

---

## 👨‍💻 Author

**Darshil Sharma**
<img width="1848" height="612" alt="image" src="https://github.com/user-attachments/assets/5ebecb5a-fd2b-4972-9bb2-41a5b37eab7a" />
<img width="520" height="314" alt="image" src="https://github.com/user-attachments/assets/0b9bd5fb-058f-42c9-a098-eb3a2b2501a8" />
<img width="576" height="383" alt="image" src="https://github.com/user-attachments/assets/ba85c889-a280-4c20-a354-9c180fc31b0b" />
<img width="933" height="323" alt="image" src="https://github.com/user-attachments/assets/d4cb0bd3-19c6-40e3-9ffb-8bfeb366230e" />


---

## 📄 License

This project is open-source and available under the MIT License.
