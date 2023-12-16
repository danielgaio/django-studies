# django-studies

Mini projects to learn Django.

## How to run the server

> python manage.py runserver

Optionally:

> python manage.py runserver 8080

To accept connections from any IP address:

> python manage.py runserver 0.0.0.0:8000

## Create a new app on the project

> python manage.py startapp polls

## Run migrations

Will run migrations for INSTALLED_APPS in settings.py

> python manage.py migrate

# Make migrations

Will create migrations for INSTALLED_APPS in settings.py

> python manage.py makemigrations <app_name>

# Verify what sql commands will be run when applying the migrations

The number at the end is the migration number

> python manage.py sqlmigrate <app_name> 0001

# Apply migrations

> python manage.py migrate

# Open a shell in the project

> python manage.py shell

# Creating an admin user to access the admin page

> python manage.py createsuperuser

# Run tests
Will run tests for INSTALLED_APPS in settings.py. Will run all tests in the tests.py file.

> python manage.py test <app_name>