#  CREACION DE ENTORNO VIRTUAL
---

$ conda create -n app_pp_e1 python=3.11

# COMANDO DEL FRAMEWORK DJANGO
---

$ pip install django

$ django-admin startproject Proyecto1

$ cd Proyecto1

$ python manage.py help

$ cd Proyecto1

List:

- init.py, settings.py , urls.py, wsgi.py

# ACTIVAR EL PROYECTO
---
* $ python manage.py migrate

* $ python manage.py runserver

# Instalar el Paquete Bootstrap4

$ pip install django-bootstrap4