# DEMO project
This is a simple project demonstrating how to integrate multiple apps
in the Django framework, and deploy using gunicorn + nginx

## Create django project
django-admin.py startproject <projectname>

## Add app
python manage.py startapp <appname>

Add the <appname> to the INSTALL_APPS list in settings.py

