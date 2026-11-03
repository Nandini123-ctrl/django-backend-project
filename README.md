# Final Backend Project (Django REST Framework + Swagger)

This is a complete, production-ready Django REST Framework backend application built for the practical assignment.

## Features
- **Django REST Framework (DRF)** CRUD API endpoints for resource management.
- **PostgreSQL** integration ready with environment variable configuration.
- **Swagger UI & ReDoc** API documentation via `drf-yasg`.
- **Environment management** using `python-dotenv`.

## Setup Instructions

1. **Clone and Extract**:
   Download and extract this project folder.

2. **Create Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment**:
   Copy `.env.example` to `.env` and fill in your local settings:
   ```bash
   cp .env.example .env
   ```

5. **Run Migrations & Server**:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver
   ```

6. **API Documentation**:
   Access Swagger UI at `http://127.0.0.1:8000/swagger/`
