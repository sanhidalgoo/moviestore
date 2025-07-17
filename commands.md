# Djando useful commands

## Creating a django project

```bash
django-admin startproject moviestore
```

## Running local web server
```bash
python3 manage.py runserver
```

## Adding an app to the current django project
```bash
python3 manage.py startapp home
```

## Creating movies app
```bash
python3 manage.py startapp movie
```

## Making migrations and execute migrations (Every time a model is changed)
```bash
python3 manage.py makemigrations
python3 manage.py migrate
```
## Creating Django project superuser
```bash
python3 manage.py createsuperuser

python3 manage.py changepassword <username>
```