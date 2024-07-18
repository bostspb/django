# Private Shop via Django

## Create project & App
```bash
# Create project
conda activate django
django-admin startproject private_shop

# Create App `Catalog`
cd private_shop
python manage.py startapp catalog
```

## Start App
```bash
conda activate django
cd private_shop
python manage.py runserver
```

## Migration DB
```bash
python manage.py makemigrations
python manage.py migrate
```

## Create Superuser
```bash
python manage.py createsuperuser
```

## Change for Production Server
- `private_shop/private_shop/settings.py`
  - `SECRET_KEY`
  - `DEBUG`

