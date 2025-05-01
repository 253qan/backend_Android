# 📘 API Documentation

Base URL: `http://127.0.0.1:8000`

---

## Authentication

### Register
- **URL**: `/api/register`
- **Method**: `POST`
- **Request Body**:
```json{
    "user": {
        "name": "Aisyah",
        "email": "acil@gmail.com",
        "phone_number": "098754633774",
        "birth_date": "12 April 2003",
"password": "your_password",
"password_confirmation": "your_password"}
}

### Login
- **URL**: `/api/login`
- **Method**: `POST`
- **Request Body**:
```json
{
  "email": "user@example.com",
  "password": "your_password"
}

### Logout
- **URL**: `/api/logout`
- **Method**: `POST`
- **Request Body**:
