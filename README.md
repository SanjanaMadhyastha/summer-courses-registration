This project is a Django application designed to facilitate the registration of students from various colleges for summer technical courses. Through a user-friendly web interface, students can register by providing their name, college, and course details, with all data being securely stored in an SQLite database.
Features
The application includes features such as user registration for summer courses, an admin panel for managing registrations, form validation and submission, and the use of an SQLite database for data storage.

# Requirements# :
To run this project, you need Python 3.x and Django 3.x or later.

# Installation #:
To install the project, first, clone the repository using git clone https://github.com/Sanjana Madhyastha/summer-courses-registration.git and navigate to the project directory with cd summer-courses-registration. Next, create and activate a virtual environment using python -m venv venv and source venv/bin/activate (on Windows, use venv\Scripts\activate). Install the required packages with pip install -r requirements.txt. Apply migrations to set up the database using python manage.py makemigrations and python manage.py migrate. Create a superuser for accessing the admin panel using python manage.py createsuperuser, and finally, start the development server with python manage.py runserver.

# Usage #:
To use the application, access the user registration form at http://127.0.0.1:8000/app1/register/, fill out the form with your name, college, and course details, and submit to register for a course. For admin access, go to http://127.0.0.1:8000/admin/, log in with the superuser credentials, and manage registrations through the admin interface.

# Project Structure #:
The project structure includes key directories and files such as summer_courses/ containing manage.py, db.sqlite3, and settings files, and registration/ containing models, views, forms, and templates for registration and success pages
