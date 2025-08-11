# Django Blog Application

A simple Django blog app for creating, editing, and deleting posts with comment management and approval system.

## Features

- Create, edit, and delete blog posts
- Comment system with admin approval
- User authentication and authorization
- Draft and publish functionality

## Quick Setup

1. **Clone and setup**
   ```bash
   git clone <repository-url>
   cd django_blog
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install and run**
   ```bash
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py createsuperuser  # Optional, for admin access
   python manage.py runserver
   ```

3. **Access the application**
   - Blog: http://127.0.0.1:8000/
   - Admin: http://127.0.0.1:8000/admin/

## Tech Stack

Django 5.2.5, SQLite, HTML/CSS
