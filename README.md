## start django:

python -m venv venv

source venv/bin/activate

pip install django

django-admin startproject projectname

cd projectname

./manage.py runserver

./manage.py migrate

./manage.py createsuperuser

./manage.py startapp appname

settings.py - register appname

after cteating Models - ./manage.py makemigrations | ./manage.py migrate

register Model in Admin - from .models import ModelName | admin.site.register(ModelName)
