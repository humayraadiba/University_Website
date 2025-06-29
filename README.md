# University Web Portal 🏫

This is a demo web portal built with Django for university announcements, routines, and news posts.  
It mimics a basic CMS (Content Management System) where admin users can post university updates from the Django admin panel.

---

## 🔧 Features

- 📰 Post important university news and notices
- 🖼️ Display a banner and University of Chittagong logo
- 🎨 Responsive layout inspired by the Cumilla Education Board website
- 🛠 Built using Django 5.2.3 and Python 3.11
- 🧑‍💻 Admin panel access for managing content

---

## 📸 Home Page Overview

- University Logo: Top left corner
- Banner Slideshow: Center top of the home page
- Latest Notices: Appears on the right side below the banner
- Background: Standard color theme with better alignment

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have installed:

- Python 3.11+
- pip
- Git
- Django (already installed using `pip install django`)

### ▶️ Setup Instructions

```bash
# Clone this repository
git clone https://github.com/your-username/universityweb_task.git

# Navigate into the folder
cd universityweb_task

# Create and activate virtual environment
python -m venv venv
venv\Scripts\activate     # Windows

# Install Django
pip install django

# Run migrations
python manage.py migrate

# Create superuser to access admin panel
python manage.py createsuperuser

# Start the server
python manage.py runserver
