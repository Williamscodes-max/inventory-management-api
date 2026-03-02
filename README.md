# Inventory Management API

## Project Description
The Inventory Management API is a backend RESTful service built with Django and Django REST Framework.  
It allows users to manage inventory items and categories, providing basic CRUD operations for tracking stock and organizing products.

This project was developed as part of the ALX Backend Engineering Capstone Project to demonstrate backend development skills, API design, and database modeling.

---

## Features
- Create, read, update, and delete inventory items
- Create and manage item categories
- RESTful API responses in JSON format
- Django Admin interface for managing inventory data

---

## Tech Stack
- Python
- Django
- Django REST Framework
- SQLite (development database)

---

## Project Structure

inventory-capstone/
├── inventory_project/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── inventory/
│ ├── models.py
│ ├── serializers.py
│ ├── views.py
│ ├── urls.py
│ └── admin.py
├── manage.py
├── requirements.txt
└── README.md


---

## Setup Instructions (Local Development)

1. Clone the repository:

git clone https://github.com/Williamscodes-max/inventory-management-api.git


2. Navigate into the project directory:

cd inventory-management-api


3. Create and activate a virtual environment:

python -m venv venv
venv\Scripts\activate


4. Install dependencies:

pip install -r requirements.txt


5. Run database migrations:

python manage.py migrate


6. Start the development server:

python manage.py runserver


The API will be available at:

http://127.0.0.1:8000/


---

## API Endpoints (Main)

### Items
- `GET /items/` – List all inventory items
- `POST /items/` – Create a new item
- `GET /items/<id>/` – Retrieve a single item
- `PUT /items/<id>/` – Update an item
- `DELETE /items/<id>/` – Delete an item

### Categories
- `GET /categories/` – List all categories
- `POST /categories/` – Create a category

---

## Author
**Williams**  
ALX Backend Engineering Program

---

## Notes
This project was built during the ALX capstone phase.  
Some features may still be improved, but the core backend functionality is complete and working




## Deployment Notes

This project uses SQLite for local development and testing.

For deployment, the API service was successfully deployed and is publicly accessible.  
A production database (e.g., PostgreSQL) was not configured, as it was optional for this task.

SQLite was used for development; production DB setup was optional for this task.