# django-books

simple django rest-framework app
Book api

# for virtual enviroment

```bash
pipenv shell
```

# Installation

```bash
pipenv install django

pipenv install djangorestframework
```

# Or for global

```bash
pip install django
    or
sudo apt install python3-django
```

```bash
pip install djangorestframework
```

# Start development

```bash
django-admin startproject base
```

```bash
cd base
python3 manage.py startapp books
```

# Migration

```bash
python3 manage.py makemigrations books
```

```bash
python3 manage.py migrate
```

# Running the app

```bash
python3 manage.py runserver
```

Starting development server at http://127.0.0.1:8000/
