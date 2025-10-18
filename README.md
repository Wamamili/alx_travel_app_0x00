# ALX Travel App 0x00

## Overview
Backend for a travel listing platform — includes models, serializers, and a custom seeder.

## Setup
```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py seed
python manage.py runserver
Features

Django Models: Listing, Booking, Review

DRF Serializers with nested relationships

Custom Seeder Command (python manage.py seed)

Swagger API Docs at /swagger/


---

## ✅ Final Project Structure



alx_travel_app_0x00/
│── alx_travel_app/
│ ├── settings.py
│ ├── urls.py
│
│── listings/
│ ├── models.py
│ ├── serializers.py
│ ├── views.py
│ ├── urls.py
│ ├── management/
│ │ └── commands/
│ │ └── seed.py
│
│── manage.py
│── requirements.txt
│── README.md
│── .env





www