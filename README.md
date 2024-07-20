# lab_flask2
Flask Sign Up/Sign In Interface

Project Overview

This project implements a Sign Up/Sign In interface using Flask and SQLite. The application includes basic and required features of a simple login/signup page. Additional functionalities and aesthetic improvements have also been made.

Features

Sign In Page

	•	Users can enter their username and password to sign in.
	•	Upon successful sign-in, users are redirected to the secret page.
	•	The username and password are saved in the SQLite database.

Sign Up Page

	•	Users can register by providing their first name, last name, email address, password, and confirm password.
	•	Passwords are validated to meet the criteria:
	•	Must contain a lowercase letter.
	•	Must contain an uppercase letter.
	•	Must end in a number.
	•	Must be at least 8 characters long.
	•	Passwords are hashed using SHA-256 before storing in the database.
	•	Email addresses are checked to ensure they are unique.
	•	Upon successful registration, users are redirected to the thank you page.

 Project Structure 
 lab7_flask_app/
│
|--users.db
├── app.py
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── secretpage.html
│   └── thankyou.html

Prerequisites

	•	Python 3.7+
	•	Flask
	•	Flask-SQLAlchemy
	•	Werkzeug

Running the Application

python app.py

Open your browser and navigate to:
http://127.0.0.1:5000

Usage

	•	Sign In: Enter your username and password to access the secret page.
	•	Sign Up: Register a new account by filling in the required fields. Ensure that your password meets the specified criteria.

