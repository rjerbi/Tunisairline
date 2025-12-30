## Tunisairline :
Tunisair Management System is a web-based flight reservation and management application developed using Django.
The system allows users to search for available flights and make reservations, while administrators can manage airlines, airports, flights, and reservations through a secure dashboard.

## Features :
- Public flight search and reservation system.
- User registration, login, and authentication.
- Luggage weight validation.
- User profile management and password update.
- Admin dashboard with system statistics.
- Airlines management (add, update, delete).
- Airports management (add, update, delete).
- Flights management (add, update, delete, view details).
- Reservations management (view, update status, delete).
- Secure access using Django authentication and decorators.

## Requirements :
- Python
- Django
- PostgreSQL

## Installation:
- Install project dependencies with:
  pip install -r requirements.txt

## Run the Project :
- python manage.py makemigrations
- python manage.py migrate
- python manage.py createsuperuser
- python manage.py runserver

- Open your browser at:
  http://127.0.0.1:8000/


