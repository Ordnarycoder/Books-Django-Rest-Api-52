# 📚 Django REST Framework - Book API

A simple REST API built with Django and Django REST Framework (DRF) for managing books. This API supports basic CRUD (Create, Read, Update, Delete) operations.

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/Ordnarycoder/Books-Django-Rest-Api-52.git
```

### 2. Set Up Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install django djangorestframework
```

### 4. Migrate Database

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the Server

```bash
python manage.py runserver
```

Open your browser and navigate to:
```
http://localhost:8000/api/books/
```

## 🔧 API Endpoints

| Method | Endpoint           | Description            |
|--------|--------------------|------------------------|
| GET    | `/api/books/`      | List all books         |
| POST   | `/api/books/`      | Create a new book      |
| GET    | `/api/books/{id}/` | Retrieve a single book |
| PUT    | `/api/books/{id}/` | Update a book          |
| DELETE | `/api/books/{id}/` | Delete a book          |

## 📖 Model Fields

- `title` (string)
- `author` (string)
- `published_date` (date)

## ⚙️ Built With

- **[Django](https://www.djangoproject.com/)** - Web framework
- **[Django REST Framework](https://www.django-rest-framework.org/)** - API toolkit

## 🤝 Contribution

Contributions, issues, and feature requests are welcome!

## 📄 License

Feel free to use this project for your learning and portfolio purposes.