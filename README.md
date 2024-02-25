# ApuntesDjango

django-admin startproject mysite

cd mysite

python manage.py runserver

python manage.py startapp polls

crear urls en la app y modificar views y admins

Views
```
from django.http import HttpResponse


def index(request):
    return HttpResponse("Hello, world. You're at the polls index.")
```
