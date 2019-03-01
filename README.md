# This project is a introduction to Django framework.

# Useful commands:
- sudo pip install virtualenv
- virtualenv name_environmetns or virtualenv -p /usr/bin/python3.6 name_environments
- source name_environments/bin/activate
- pip install django
- pip list
- pip freeze --local > requirements.txt 
- deactivate
- django-admin (django commands list)
- django-admin startproject django_project
- python manage.py runserver
- Access by http://127.0.0.1:8000/ or http://localhost:8000/
- python manage.py startapp blog (Create new app called 'blog')
- pip install django-crispy-forms

# For every change in db it will need to execute the following commands
- python manage.py makemigrations (Create migrtions)
- python manage.py migrate
- python manage.py sqlmigrate blog 0001 (To see SQL code)

