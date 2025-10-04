# Inventory Management App

## A simple Django-based inventory management system that allows users to create, view, update, and delete products. The project uses Bootstrap for styling and Django forms for easy CRUD operations.

## Installation

### 1. Clone the repository:
```
git clone https://github.com/zijadDj/InventoryApp.git
cd InventoryApp
```

### 2. Create and activate a virtual environment:
```
python3 -m venv venv
source venv/bin/activate - For linux
venv\Scripts\activate  - For Windows
```
### 3. Install dependencies:
```
pip install django
pip install django-crispy-forms
pip install crispy-bootstrap5
```
### 4. Apply migrations:
```
python manage.py migrate
```

### 5. Run the development server:
```
python manage.py runserver
```

Open your browser at http://127.0.0.1:8000