# Secure Login System

## Features
- User registration and login
- Password hashing
- Input validation
- SQLAlchemy ORM (helps avoid raw SQL injection)
- Session management
- Logout
- SQLite database
- Clean responsive UI

## Run
1. Install Python 3.
2. Open terminal in this folder.
3. Run:
   pip install -r requirements.txt
4. Run:
   python app.py
5. Open http://127.0.0.1:5000

## Important
For a real deployment, set a strong SECRET_KEY environment variable, disable debug mode, use HTTPS, add CSRF protection, rate limiting, secure cookie settings, and consider Argon2/bcrypt.
