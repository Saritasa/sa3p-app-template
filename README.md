## Django app template

This is a template for creating a new reusable application for Django. This uses the template feature added to the startapp command in Django 1.4.

To start a new app with this template:
```bash
django-admin startapp --template=https://github.com/Saritasa/sa3p-app-template/archive/develop.zip <app_name>
```

This command creates app with this file tree:
```bash
├── api
│   ├── __init__.py
│   ├── exceptions.py
│   ├── serializers.py
│   ├── urls.py
│   └── views.py
├── migrations
│   └── __init__.py
├── tests
│   ├── __init__.py
│   ├── test_api.py
│   └── test_models.py
├── __init__.py
├── admin.py
├── apps.py
├── factories.py
├── models.py
└── views.py
```
