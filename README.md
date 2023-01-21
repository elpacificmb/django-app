# django-app

## This process is for Windows Os

Installing Python with the setup

Creating a Virtual environment with python -m venv my_env

Activating the virtual env with .\my_env\Scripts\activate

Installing Django with pip install Django~=4.1.0

### Creating a Django project
Creating a default Django project with django-admin startproject myproject

Opening the project folder with cd myproject

Migrating database with python manage.py migrate

Starting the dev server with python manage.py runserver

Open this link in the browser http://127.0.0.1:8000/


### Creating a Django app
Creating a default django app with python manage.py startapp myapp

Opening the project folder with cd myapp

### Using Python shell in a Django project
python manage.py shell

### Creating an Initial migration for Models
python manage.py makemigrations blog

### Inspect SQL output from migration
python manage.py sqlmigrate blog 0001

### Applying all migrations
python manage.py migrate

### Creating a superuser for admin site
python manage.py createsuperuser

Admin site link http://127.0.0.1:8000/admin/
Blog site link http://127.0.0.1:8000/blog/


### Creating requirements.txt file
pip freeze > requirements.txt

### Installing packages from requirements.txt file
pip install requirements.txt
