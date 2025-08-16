# Flask GMail and Google Sign-in Project

A simple Flask web application demonstrating user authentication with local registration (username/password) and Google OAuth, including email confirmation for new users.

## 🌟 Features

- **Local User Registration:** Sign up with a username, email, and password.
- **Password Hashing:** Secure password storage using `werkzeug.security`.
- **Email Confirmation:** Account activation via a secure, time-sensitive link sent to the user's email.
- **Google OAuth 2.0:** Seamless sign-in using your Google account with `Flask-Dance`.
- **Database Integration:** User and OAuth data are stored in a SQLite database (`glu.db`) using `Flask-SQLAlchemy`.

## 📂 Project Structure