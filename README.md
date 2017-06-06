# First Django App

Results of the *Writing your first Django app* series on djangoproject.com, as of Djano 1.11:

1. [Part 1](https://docs.djangoproject.com/en/1.11/intro/tutorial01/) - 8261c24
1. [Part 2](https://docs.djangoproject.com/en/1.11/intro/tutorial02/) - bcf9e99
1. [Part 3](https://docs.djangoproject.com/en/1.11/intro/tutorial03/) - 8f5eefb
1. [Part 4](https://docs.djangoproject.com/en/1.11/intro/tutorial04/) - cc1424f
1. [Part 5](https://docs.djangoproject.com/en/1.11/intro/tutorial05/) - 050b465
1. [Part 6](https://docs.djangoproject.com/en/1.11/intro/tutorial06/) - 2645464
1. [Part 7](https://docs.djangoproject.com/en/1.11/intro/tutorial07/) - 12d9a73

# Installation

## Requirements

- Python 3+
- Pipenv
- Django 1.11+

## Steps

```
apt-get install python3 python3-pip
pip install pipenv
git clone https://github.com/cdubz/first-django-app.git
cd first-django-app/
pipenv install --three
pipenv shell
cd mysite
python manage.py runserver
```

# Settings

The default login and password for the admin site is `admin:admin`.
