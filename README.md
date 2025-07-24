# User Login & App

A simple and secure user login system with a microblog-style homepage built using Flask, SQLAlchemy, Flask-WTF, and a modern Bootstrap 5 UI. Users can register, log in, and view a feed of sample posts.

---

## Features

- User registration and secure login/logout
- Password hashing with Werkzeug
- SQLite database using SQLAlchemy ORM
- Flask-Login session management
- Modern responsive UI using Bootstrap 5
- Flask-Migrate for database migrations

---

## Project Structure
User Logins/
├── run.py # App runner
├── app/
│ ├── init.py # App factory & config setup
│ ├── config.py # Config class
│ ├── routes.py # Routes for login, register, home
│ ├── models.py # User & Post models
│ ├── forms.py # Flask-WTF forms
│ └── templates/ # HTML templates
│ ├── base.html
│ ├── index.html
│ ├── login.html
│ └── register.html
├── migrations/ # Auto-generated migration scripts
└── app.db # SQLite database (auto-created)


---

## Setup Instructions

### 1. Install Requirements

Make sure you have Python 3.10+ installed.

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
