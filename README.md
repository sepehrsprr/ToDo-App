# Modern Todo App

A modern, feature-rich todo application built with Django. This application includes user authentication, task categories, due dates, priority levels, and a responsive UI.

## Features

- User Authentication (Register, Login, Logout)
- Create, Read, Update, and Delete Tasks
- Task Categories and Tags
- Priority Levels
- Due Dates
- Task Filtering and Search
- Responsive Modern UI
- Dark/Light Mode Toggle

## Setup Instructions

1. Clone the repository
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run migrations:
   ```bash
   python manage.py migrate
   ```
5. Create a superuser (admin):
   ```bash
   python manage.py createsuperuser
   ```
6. Run the development server:
   ```bash
   python manage.py runserver
   ```
7. Visit http://127.0.0.1:8000 in your browser

## Tech Stack

- Django 5.0.1
- Bootstrap 5
- Crispy Forms
- SQLite (default database)
- JavaScript (for interactive features) 