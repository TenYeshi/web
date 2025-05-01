Admin Dashboard + Flask Web App

This project combines a responsive Admin Dashboard UI built with Bootstrap 5.3 and a basic Flask web application backend. It includes user authentication, flash messaging, and a structured layout for building full-featured web applications.

🧹 Components

Admin Dashboard (Frontend)

A responsive, mobile-friendly dashboard layout with:

Responsive top navbar with logo and user dropdown

Collapsible sidebar using Bootstrap Offcanvas for smaller screens

Main content area with dashboard cards (users, revenue, errors)

Dark Bootstrap theme for a sleek modern look

Integrated user login name dropdown

Flask Web App (Backend)

A basic Flask-based web application with routes for homepage, login, signup, contact, and about. It includes user interaction through POST forms and handles basic flash messaging for feedback.

✨ Features

Frontend Features

🖥️ Responsive Admin Dashboard UI

☞ Offcanvas sidebar for mobile

📊 Dashboard cards for key metrics

👤 User dropdown with Profile, Settings, Logout

🌃 Dark Bootstrap styling

Flask Web App Features

🏠 Home Page (/, /index.html)

👤 Login Page (/login.html)

📝 Signup Logic (POST to /login.html)

🔐 Admin Login with session support

📄 Contact Page (/contact.html)

ℹ️ About Page (/about.html)

🔔 Flash messaging for feedback

🧠 Simple credential check for admin (admin:123)

🚀 Getting Started

1. Prerequisites

Make sure you have Python 3 installed.

Install Flask using pip:

pip install flask

2. Run the Flask App

python app.py

3. Access the App

Visit http://127.0.0.1:5000 in your browser.

📁 Project Structure

/project-root
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── contact.html
│   └── about.html
├── static/
│   └── img/
│       └── logo.png
├── app.py
├── README.md

🔧 Dependencies

Bootstrap 5.3

Flask

(Optional) Font Awesome for icons

📷 Screenshot

(Add a UI screenshot here)

📜 License

MIT License — Free to use and modify.

This project is intended solely for educational purposes and learning full-stack web development. Acknowledgements: I also took help from AI and other resources.
