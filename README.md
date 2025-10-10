# Inventory Management App

## A simple Django-based inventory management system that allows users to create, view, update, and delete products. The project uses Bootstrap for styling and Django forms for easy CRUD operations.

## Installation

### 1. Clone the repository:
```
git clone https://github.com/zijadDj/InventoryApp.git
cd InventoryApp
```

### 2. Build and run the containers:
```
docker compose up --build

```
### 3. Apply database migrations:
```
docker compose exec web python manage.py migrate

```

Open your browser at http://127.0.0.1:8000