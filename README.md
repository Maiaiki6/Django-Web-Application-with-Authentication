# Django Blog Application with Authentication

This is a fully functional Django web application featuring user authentication, including registration, login, logout, and password reset functionality. The application is a blog where users can create and edit posts.

## Features

- User registration and login
- Password reset via email (console backend for development)
- User roles: regular users and staff/admin users
- Blog posts with CRUD operations
- Secure password handling using Django's built-in authentication system

## Setup

1. Ensure you have Python installed.
2. Create a virtual environment and activate it.
3. Install dependencies: `pip install django`
4. Run migrations: `python manage.py migrate`
5. Create a superuser: `python manage.py createsuperuser`
6. Run the server: `python manage.py runserver`

## Usage

- Visit the homepage to view blog posts.
- Register a new account or login.
- Logged-in users can create new posts.
- Staff users can edit any post; regular users can only edit their own posts.
- Use the password reset feature if needed.

## Admin

Access the admin panel at `/admin/` with superuser credentials to manage users and posts.