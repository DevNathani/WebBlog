
# 📝 WebBlog – Flask-Based Blogging Platform

A feature-rich blog application built using **Flask** as the backend framework, **HTML + Bootstrap** for the frontend, and **SQLite** as the database. This app includes user authentication, post creation/editing, password reset via email, and profile picture management.

---

## 🚀 Tech Stack

**Frontend**  
- HTML  
- Bootstrap  
- Jinja2 (templating engine)

**Backend**  
- Python  
- Flask  
- Flask-WTF (form handling)  
- Flask-Mail (for password reset emails)  
- Flask-Bcrypt (password hashing)  
- Flask-Login (session-based user authentication)  
- JWT (JSON Web Tokens – used for password reset)  
- Pillow (PIL) – for image processing  
- SQLAlchemy ORM  
- SQLite (lightweight DB)

---

## 📁 Features

- User registration & login with hashed passwords  
- Profile editing with image upload & processing  
- JWT-powered secure password reset via email  
- Create, edit, delete blog posts  
- Custom error pages (404, 403, 500)  
- Flash messages for UI feedback  
- Modular Flask Blueprints structure

---

## 🛠 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/WebBlog.git
cd WebBlog

# On Windows
python -m venv venv
venv\Scripts\activate

# On Unix/macOS
python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt

## Setup Environment Variables
FORUM_SECRET
SQLALCHEMY_DATABASE_URI
EMAIL_USER
EMAIL_PASS