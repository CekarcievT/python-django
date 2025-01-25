# PYTHON-DJANGO

1. install python
2. install pip
3. install django  and django rest framework with command => pip install django djangorestframework

## Create a project
Create a new project with the command "django-admin startproject simplecrud"

## Create a API app inside the project
1. Position inside the project simplecrud with the command "cd simplecrud"
2. Type the command => python manage.py startapp api

## Include installed app in the main app
Open the file settings.py and add "rest_framework" and "api" in the INSTALLED_APPS section

## Generate a migration
After the model is created, run the command => python manage.py makemigrations

## Run the app
To run the app use the command "python manage.py runserver
