# Django Simple Authentication System

This is a simple authentication system built using Django.

It includes:

- User Registration
- User Login
- User Logout
- Protected Dashboard
- Session Handling
- SQLite Database (default)

---

## 🚀 Features

- User registration with username, email, and password
- Secure password hashing
- Login authentication using Django built-in auth
- Logout functionality
- Dashboard accessible only to logged-in users
- Flash messages for success and error alerts

---

## 🛠️ Technologies Used

- Python
- Django
- SQLite3 (Default Django Database)
- HTML

---


---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository

### 2️⃣ Create Virtual Environment (Optional but Recommended)

### 3️⃣ Install Dependencies

### 4️⃣ Apply Migrations

### 5️⃣ Run the Server

---

## 🔐 Authentication Flow

- `create_user()` → Creates user with hashed password
- `authenticate()` → Verifies username & password
- `login()` → Creates session
- `logout()` → Destroys session
- `request.user` → Returns logged-in user

---

## 📌 Important Tables in SQLite

- auth_user
- django_session
- django_admin_log
- django_migrations

---

## 📖 Future Improvements

- Add password validation
- Use Django Forms
- Add email verification
- Connect MySQL/PostgreSQL
- Add profile page
- Use Bootstrap for UI styling

---

## 👨‍💻 Author

Your Name

---

## 📜 License

This project is for educational purposes.

